//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[RotateGestureDetector](index.md)

# RotateGestureDetector

[androidJvm]\
class [RotateGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateGestureListener](-on-rotate-gesture-listener/index.md), handler: [Handler](https://developer.android.com/reference/kotlin/android/os/Handler.html)?)

###  Detects rotation transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s

The [OnRotateGestureListener](-on-rotate-gesture-listener/index.md) callback will notify users when a particular gesture event has occurred.

This class should only be used with [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s reported via touch.

To use this class:

- 
   Create an instance of the [RotateGestureDetector](index.md) for your [android.view.View](https://developer.android.com/reference/kotlin/android/view/View.html)
- 
   In the [android.view.View.onTouchEvent](https://developer.android.com/reference/kotlin/android/view/View.html#ontouchevent) method ensure you call [onTouchEvent](on-touch-event.md). The methods defined in your callback will be executed when the events occur.

## Parameters

androidJvm

| | |
|---|---|
| context | the application's context |
| listener | the listener invoked for all the callbacks, this must not be null |
| handler | the handler to use for running deferred listener events |

## Constructors

| | |
|---|---|
| [RotateGestureDetector](-rotate-gesture-detector.md) | [androidJvm]<br>fun [RotateGestureDetector](-rotate-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateGestureListener](-on-rotate-gesture-listener/index.md), handler: [Handler](https://developer.android.com/reference/kotlin/android/os/Handler.html)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |
| [OnRotateGestureListener](-on-rotate-gesture-listener/index.md) | [androidJvm]<br>interface [OnRotateGestureListener](-on-rotate-gesture-listener/index.md)<br>If you want to listen for all the different gestures then implement this interface. If you only want to listen for a subset it might be easier to extend [SimpleOnRotateGestureListener](-simple-on-rotate-gesture-listener/index.md). |
| [SimpleOnRotateGestureListener](-simple-on-rotate-gesture-listener/index.md) | [androidJvm]<br>open class [SimpleOnRotateGestureListener](-simple-on-rotate-gesture-listener/index.md) : [RotateGestureDetector.OnRotateGestureListener](-on-rotate-gesture-listener/index.md)<br>rotation-related events. |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>open fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>appropriate |
| [reset](reset.md) | [androidJvm]<br>fun [reset](reset.md)() |

## Properties

| Name | Summary |
|---|---|
| [context](context.md) | [androidJvm]<br>val [context](context.md): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) |
| [currentAngle](current-angle.md) | [androidJvm]<br>var [currentAngle](current-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>through the focal point |
| [currentPressure](current-pressure.md) | [androidJvm]<br>var [currentPressure](current-pressure.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [currentSpan](current-span.md) | [androidJvm]<br>var [currentSpan](current-span.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [focusX](focus-x.md) | [androidJvm]<br>var [focusX](focus-x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null<br>If a gesture is in progress, the focal point is between each of the pointers forming the gesture. If a gesture is ending, the focal point is the location of the  remaining pointer on the screen. If [isGestureInProgress](is-gesture-in-progress.md) would return false, the result of this function is null. |
| [focusY](focus-y.md) | [androidJvm]<br>var [focusY](focus-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null<br>If a gesture is in progress, the focal point is between each of the pointers forming the gesture. If a gesture is ending, the focal point is the location of the  remaining pointer on the screen. If [isGestureInProgress](is-gesture-in-progress.md) would return false, the result of this function is null. |
| [handler](handler.md) | [androidJvm]<br>var [handler](handler.md): [Handler](https://developer.android.com/reference/kotlin/android/os/Handler.html)? = null |
| [isGestureInProgress](is-gesture-in-progress.md) | [androidJvm]<br>var [isGestureInProgress](is-gesture-in-progress.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [listener](listener.md) | [androidJvm]<br>var [listener](listener.md): [RotateGestureDetector.OnRotateGestureListener](-on-rotate-gesture-listener/index.md) |
| [previousAngle](previous-angle.md) | [androidJvm]<br>var [previousAngle](previous-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f<br>progress through the focal point. |
| [previousPressure](previous-pressure.md) | [androidJvm]<br>var [previousPressure](previous-pressure.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [previousSpan](previous-span.md) | [androidJvm]<br>var [previousSpan](previous-span.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [rotation](rotation.md) | [androidJvm]<br>var [rotation](rotation.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null<br>This value is defined as ([currentAngle](current-angle.md) / [previousAngle](previous-angle.md)). |
| [tentativeFirstRotateEvent](tentative-first-rotate-event.md) | [androidJvm]<br>var [tentativeFirstRotateEvent](tentative-first-rotate-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [timeDelta](time-delta.md) | [androidJvm]<br>var [timeDelta](time-delta.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null<br>and the current GestureDetector event |
