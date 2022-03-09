//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[DragGestureRecognizer](index.md)

# DragGestureRecognizer

[androidJvm]\
open class [DragGestureRecognizer](index.md) : [BaseGestureRecognizer](../-base-gesture-recognizer/index.md)&lt;[DragGesture](../-drag-gesture/index.md)&gt; 

Gesture Recognizer for when the user performs a drag motion on the touch screen.

## Constructors

| | |
|---|---|
| [DragGestureRecognizer](-drag-gesture-recognizer.md) | [androidJvm]<br>open fun [DragGestureRecognizer](-drag-gesture-recognizer.md)(gesturePointersUtility: [GesturePointersUtility](../-gesture-pointers-utility/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureStartedListener](-on-gesture-started-listener/index.md) | [androidJvm]<br>interface [OnGestureStartedListener](-on-gesture-started-listener/index.md) : [BaseGestureRecognizer.OnGestureStartedListener](../-base-gesture-recognizer/-on-gesture-started-listener/index.md)&lt;[DragGesture](../-drag-gesture/index.md)&gt; <br>Interface definition for a callbacks to be invoked when a [DragGesture](../-drag-gesture/index.md) starts. |

## Functions

| Name | Summary |
|---|---|
| [addOnGestureStartedListener](../-base-gesture-recognizer/add-on-gesture-started-listener.md) | [androidJvm]<br>open fun [addOnGestureStartedListener](../-base-gesture-recognizer/add-on-gesture-started-listener.md)(listener: [BaseGestureRecognizer.OnGestureStartedListener](../-base-gesture-recognizer/-on-gesture-started-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |
| [onTouch](../-base-gesture-recognizer/on-touch.md) | [androidJvm]<br>open fun [onTouch](../-base-gesture-recognizer/on-touch.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [removeOnGestureStartedListener](../-base-gesture-recognizer/remove-on-gesture-started-listener.md) | [androidJvm]<br>open fun [removeOnGestureStartedListener](../-base-gesture-recognizer/remove-on-gesture-started-listener.md)(listener: [BaseGestureRecognizer.OnGestureStartedListener](../-base-gesture-recognizer/-on-gesture-started-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |
