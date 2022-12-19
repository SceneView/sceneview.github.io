//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[RotateGestureDetector](index.md)

# RotateGestureDetector

[androidJvm]\
open class [RotateGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateListener](-on-rotate-listener/index.md))

Detects rotation transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s

The [OnRotateListener](-on-rotate-listener/index.md) callback will notify users when a particular gesture event has occurred

This class should only be used with [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s reported via touch.

To use this class:

- 
   Create an instance of the [RotateGestureDetector](index.md) for your [android.view.View](https://developer.android.com/reference/kotlin/android/view/View.html).
- 
   In the [android.view.View.onTouchEvent](../../io.github.sceneview.texture/-view-stream/index.md#255030538%2FFunctions%2F-1571379623) method ensure you call [onTouchEvent](on-touch-event.md). The methods defined in your callback will be executed when the events occur.

## Parameters

androidJvm

| | |
|---|---|
| context | the application's context |
| listener | the listener invoked for all the callbacks, this must not be null |

## Constructors

| | |
|---|---|
| [RotateGestureDetector](-rotate-gesture-detector.md) | [androidJvm]<br>fun [RotateGestureDetector](-rotate-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateListener](-on-rotate-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |
| [OnRotateListener](-on-rotate-listener/index.md) | [androidJvm]<br>interface [OnRotateListener](-on-rotate-listener/index.md)<br>The listener for receiving notifications when gestures occur |
| [SimpleOnRotateListener](-simple-on-rotate-listener/index.md) | [androidJvm]<br>interface [SimpleOnRotateListener](-simple-on-rotate-listener/index.md) : [RotateGestureDetector.OnRotateListener](-on-rotate-listener/index.md)<br>A convenience class to extend when you only want to listen for a subset of rotation-related events |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Accepts MotionEvents and dispatches events to a [OnRotateListener](-on-rotate-listener/index.md) when appropriate |
| [reset](reset.md) | [androidJvm]<br>fun [reset](reset.md)() |

## Properties

| Name | Summary |
|---|---|
| [currentAngle](current-angle.md) | [androidJvm]<br>var [currentAngle](current-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The average angle in radians between each of the pointers forming the gesture in progress through the focal point |
| [currentSpan](current-span.md) | [androidJvm]<br>var [currentSpan](current-span.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The current distance in pixels between the two pointers forming the gesture in progress |
| [deltaQuaternion](delta-quaternion.md) | [androidJvm]<br>val [deltaQuaternion](delta-quaternion.md): Quaternion |
| [deltaRadians](delta-radians.md) | [androidJvm]<br>val [deltaRadians](delta-radians.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [focusX](focus-x.md) | [androidJvm]<br>var [focusX](focus-x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The X coordinate of the current gesture's focal point in pixels |
| [focusY](focus-y.md) | [androidJvm]<br>var [focusY](focus-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The Y coordinate of the current gesture's focal point in pixels |
| [isGestureInProgress](is-gesture-in-progress.md) | [androidJvm]<br>var [isGestureInProgress](is-gesture-in-progress.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>`true` if a rotate gesture is in progress |
| [lastAngle](last-angle.md) | [androidJvm]<br>var [lastAngle](last-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f |
| [previousAngle](previous-angle.md) | [androidJvm]<br>var [previousAngle](previous-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The previous average angle in radians between each of the pointers forming the gesture in progress through the focal point. |
| [previousSpan](previous-span.md) | [androidJvm]<br>var [previousSpan](previous-span.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The previous distance in pixels between the two pointers forming the gesture in progress |
| [rotation](rotation.md) | [androidJvm]<br>var [rotation](rotation.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>The rotation factor in degrees from the previous rotation event to the current event |
| [rotationThreshold](rotation-threshold.md) | [androidJvm]<br>var [rotationThreshold](rotation-threshold.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f<br>The initial rotation threshold in degrees for detecting a gesture |
| [timeDelta](time-delta.md) | [androidJvm]<br>var [timeDelta](time-delta.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0<br>The time difference in milliseconds between the previous accepted GestureDetector event and the current GestureDetector event |
