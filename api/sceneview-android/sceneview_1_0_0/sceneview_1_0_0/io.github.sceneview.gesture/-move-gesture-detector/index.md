//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[MoveGestureDetector](index.md)

# MoveGestureDetector

[androidJvm]\
open class [MoveGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md))

Detects move transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s

The [OnMoveListener](-on-move-listener/index.md) callback will notify users when a particular gesture event has occurred.

This class should only be used with [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s reported via touch.

To use this class:

- 
   Create an instance of the [MoveGestureDetector](index.md) for your [android.view.View](https://developer.android.com/reference/kotlin/android/view/View.html)
- 
   In the [android.view.View.onTouchEvent](../../io.github.sceneview.texture/-view-stream/index.md#255030538%2FFunctions%2F-602047187) method ensure you call [onTouchEvent](on-touch-event.md). The methods defined in your callback will be executed when the events occur.

## Parameters

androidJvm

| | |
|---|---|
| context | the application's context |
| listener | the listener invoked for all the callbacks, this must not be null |

## Constructors

| | |
|---|---|
| [MoveGestureDetector](-move-gesture-detector.md) | [androidJvm]<br>fun [MoveGestureDetector](-move-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnMoveListener](-on-move-listener/index.md) | [androidJvm]<br>interface [OnMoveListener](-on-move-listener/index.md)<br>The listener for receiving notifications when gestures occur |
| [SimpleOnMoveListener](-simple-on-move-listener/index.md) | [androidJvm]<br>interface [SimpleOnMoveListener](-simple-on-move-listener/index.md) : [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md)<br>A convenience class to extend when you only want to listen for a subset of move-related events |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [currentMotionEvent](current-motion-event.md) | [androidJvm]<br>var [currentMotionEvent](current-motion-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [firstMotionEvent](first-motion-event.md) | [androidJvm]<br>var [firstMotionEvent](first-motion-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [lastDistanceX](last-distance-x.md) | [androidJvm]<br>var [lastDistanceX](last-distance-x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [lastDistanceY](last-distance-y.md) | [androidJvm]<br>var [lastDistanceY](last-distance-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
