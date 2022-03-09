//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[DragGesture](index.md)

# DragGesture

[androidJvm]\
open class [DragGesture](index.md) : [BaseGesture](../-base-gesture/index.md)&lt;[DragGesture](index.md)&gt; 

Gesture for when the user performs a drag motion on the touch screen.

## Constructors

| | |
|---|---|
| [DragGesture](-drag-gesture.md) | [androidJvm]<br>open fun [DragGesture](-drag-gesture.md)(gesturePointersUtility: [GesturePointersUtility](../-gesture-pointers-utility/index.md), pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureEventListener](-on-gesture-event-listener/index.md) | [androidJvm]<br>interface [OnGestureEventListener](-on-gesture-event-listener/index.md) : [BaseGesture.OnGestureEventListener](../-base-gesture/-on-gesture-event-listener/index.md)&lt;[DragGesture](index.md)&gt; <br>Interface definition for callbacks to be invoked by a [DragGesture](index.md). |

## Functions

| Name | Summary |
|---|---|
| [getTargetNode](../-twist-gesture/index.md#1898333764%2FFunctions%2F-1571379623) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getTargetNode](../-twist-gesture/index.md#1898333764%2FFunctions%2F-1571379623)(): [Node](../../io.github.sceneview.node/-node/index.md) |
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
| [delta](delta.md) | [androidJvm]<br>private val [delta](delta.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [position](position.md) | [androidJvm]<br>private val [position](position.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
