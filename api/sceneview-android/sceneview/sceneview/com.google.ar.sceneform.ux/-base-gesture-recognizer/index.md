//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[BaseGestureRecognizer](index.md)

# BaseGestureRecognizer

[androidJvm]\
abstract class [BaseGestureRecognizer](index.md)&lt;[T](index.md) : [BaseGesture](../-base-gesture/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;?&gt;

Base class for all Gesture Recognizers (i.e. DragGestureRecognizer). 

A Gesture recognizer processes touch input to determine if a gesture should start and fires an event when the gesture is started. 

To determine when an gesture is finished/updated, listen to the events on the gesture object.

## Constructors

| | |
|---|---|
| [BaseGestureRecognizer](-base-gesture-recognizer.md) | [androidJvm]<br>open fun [BaseGestureRecognizer](-base-gesture-recognizer.md)(gesturePointersUtility: [GesturePointersUtility](../-gesture-pointers-utility/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureStartedListener](-on-gesture-started-listener/index.md) | [androidJvm]<br>interface [OnGestureStartedListener](-on-gesture-started-listener/index.md)&lt;[T](-on-gesture-started-listener/index.md) : [BaseGesture](../-base-gesture/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;?&gt;<br>Interface definition for a callbacks to be invoked when a [BaseGesture](../-base-gesture/index.md) starts. |

## Functions

| Name | Summary |
|---|---|
| [addOnGestureStartedListener](add-on-gesture-started-listener.md) | [androidJvm]<br>open fun [addOnGestureStartedListener](add-on-gesture-started-listener.md)(listener: [BaseGestureRecognizer.OnGestureStartedListener](-on-gesture-started-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |
| [onTouch](on-touch.md) | [androidJvm]<br>open fun [onTouch](on-touch.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [removeOnGestureStartedListener](remove-on-gesture-started-listener.md) | [androidJvm]<br>open fun [removeOnGestureStartedListener](remove-on-gesture-started-listener.md)(listener: [BaseGestureRecognizer.OnGestureStartedListener](-on-gesture-started-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |

## Inheritors

| Name |
|---|
| [DragGestureRecognizer](../-drag-gesture-recognizer/index.md) |
| [PinchGestureRecognizer](../-pinch-gesture-recognizer/index.md) |
| [TwistGestureRecognizer](../-twist-gesture-recognizer/index.md) |
