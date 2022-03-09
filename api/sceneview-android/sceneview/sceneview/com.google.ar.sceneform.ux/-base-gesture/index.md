//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[BaseGesture](index.md)

# BaseGesture

[androidJvm]\
abstract class [BaseGesture](index.md)&lt;[T](index.md) : [BaseGesture](index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;?&gt;

Base class for a gesture. 

A gesture represents a sequence of touch events that are detected to represent a particular type of motion (i.e. Dragging, Pinching). 

Gestures are created and updated by BaseGestureRecognizer's.

## Constructors

| | |
|---|---|
| [BaseGesture](-base-gesture.md) | [androidJvm]<br>open fun [BaseGesture](-base-gesture.md)(gesturePointersUtility: [GesturePointersUtility](../-gesture-pointers-utility/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureEventListener](-on-gesture-event-listener/index.md) | [androidJvm]<br>interface [OnGestureEventListener](-on-gesture-event-listener/index.md)&lt;[T](-on-gesture-event-listener/index.md) : [BaseGesture](index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;?&gt;<br>Interface definition for callbacks to be invoked by a [BaseGesture](index.md). |

## Functions

| Name | Summary |
|---|---|
| [hasFinished](has-finished.md) | [androidJvm]<br>open fun [hasFinished](has-finished.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasStarted](has-started.md) | [androidJvm]<br>open fun [hasStarted](has-started.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [inchesToPixels](inches-to-pixels.md) | [androidJvm]<br>open fun [inchesToPixels](inches-to-pixels.md)(inches: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [justStarted](just-started.md) | [androidJvm]<br>open fun [justStarted](just-started.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onTouch](on-touch.md) | [androidJvm]<br>open fun [onTouch](on-touch.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [pixelsToInches](pixels-to-inches.md) | [androidJvm]<br>open fun [pixelsToInches](pixels-to-inches.md)(pixels: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [setGestureEventListener](set-gesture-event-listener.md) | [androidJvm]<br>open fun [setGestureEventListener](set-gesture-event-listener.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)listener: [BaseGesture.OnGestureEventListener](-on-gesture-event-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |
| [wasCancelled](was-cancelled.md) | [androidJvm]<br>open fun [wasCancelled](was-cancelled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [targetNode](target-node.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>protected open val [targetNode](target-node.md): [Node](../../io.github.sceneview.node/-node/index.md) |

## Inheritors

| Name |
|---|
| [DragGesture](../-drag-gesture/index.md) |
| [PinchGesture](../-pinch-gesture/index.md) |
| [TwistGesture](../-twist-gesture/index.md) |
