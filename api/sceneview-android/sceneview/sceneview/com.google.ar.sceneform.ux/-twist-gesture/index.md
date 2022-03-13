//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[TwistGesture](index.md)

# TwistGesture

[androidJvm]\
open class [TwistGesture](index.md) : [BaseGesture](../-base-gesture/index.md)&lt;[TwistGesture](index.md)&gt; 

Gesture for when the user performs a two-finger twist motion on the touch screen.

## Constructors

| | |
|---|---|
| [TwistGesture](-twist-gesture.md) | [androidJvm]<br>open fun [TwistGesture](-twist-gesture.md)(gesturePointersUtility: [GesturePointersUtility](../-gesture-pointers-utility/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), pointerId2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureEventListener](-on-gesture-event-listener/index.md) | [androidJvm]<br>interface [OnGestureEventListener](-on-gesture-event-listener/index.md) : [BaseGesture.OnGestureEventListener](../-base-gesture/-on-gesture-event-listener/index.md)&lt;[TwistGesture](index.md)&gt; <br>Interface definition for callbacks to be invoked by a [TwistGesture](index.md). |

## Functions

| Name | Summary |
|---|---|
| [getTargetNode](index.md#1898333764%2FFunctions%2F-1571379623) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getTargetNode](index.md#1898333764%2FFunctions%2F-1571379623)(): [Node](../../io.github.sceneview.node/-node/index.md) |
| [hasFinished](../-base-gesture/has-finished.md) | [androidJvm]<br>open fun [hasFinished](../-base-gesture/has-finished.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasStarted](../-base-gesture/has-started.md) | [androidJvm]<br>open fun [hasStarted](../-base-gesture/has-started.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [inchesToPixels](../-base-gesture/inches-to-pixels.md) | [androidJvm]<br>open fun [inchesToPixels](../-base-gesture/inches-to-pixels.md)(inches: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [justStarted](../-base-gesture/just-started.md) | [androidJvm]<br>open fun [justStarted](../-base-gesture/just-started.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onTouch](../-base-gesture/on-touch.md) | [androidJvm]<br>open fun [onTouch](../-base-gesture/on-touch.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [pixelsToInches](../-base-gesture/pixels-to-inches.md) | [androidJvm]<br>open fun [pixelsToInches](../-base-gesture/pixels-to-inches.md)(pixels: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [setGestureEventListener](../-base-gesture/set-gesture-event-listener.md) | [androidJvm]<br>open fun [setGestureEventListener](../-base-gesture/set-gesture-event-listener.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)listener: [BaseGesture.OnGestureEventListener](../-base-gesture/-on-gesture-event-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |
| [wasCancelled](../-base-gesture/was-cancelled.md) | [androidJvm]<br>open fun [wasCancelled](../-base-gesture/was-cancelled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [deltaRotationDegrees](delta-rotation-degrees.md) | [androidJvm]<br>private open val [deltaRotationDegrees](delta-rotation-degrees.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |