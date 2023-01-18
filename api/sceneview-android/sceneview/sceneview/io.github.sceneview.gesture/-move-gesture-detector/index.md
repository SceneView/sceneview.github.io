//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[MoveGestureDetector](index.md)

# MoveGestureDetector

[androidJvm]\
open class [MoveGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md))

## Constructors

| | |
|---|---|
| [MoveGestureDetector](-move-gesture-detector.md) | [androidJvm]<br>fun [MoveGestureDetector](-move-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnMoveListener](-on-move-listener/index.md) | [androidJvm]<br>interface [OnMoveListener](-on-move-listener/index.md)<br>If you want to listen for the different gestures then implement this interface. |
| [SimpleOnMoveListener](-simple-on-move-listener/index.md) | [androidJvm]<br>interface [SimpleOnMoveListener](-simple-on-move-listener/index.md) : [MoveGestureDetector.OnMoveListener](-on-move-listener/index.md)<br>move-related events |

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
