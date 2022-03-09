//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[TouchEventSystem](index.md)

# TouchEventSystem

[androidJvm]\
open class [TouchEventSystem](index.md)

Manages propagation of touch events to node's within a scene. 

The way that touch events are propagated mirrors the way touches are propagated to Android Views. 

When an ACTION_DOWN event occurs, that represents that start of a gesture. ACTION_UP or ACTION_CANCEL represents when a gesture ends. When a gesture starts, the following is done: 

- Call dispatchTouchEvent on the node that was touched as detected by scene.hitTest.
- If dispatchTouchEvent returns false, recurse upwards through the node's parents and call dispatchTouchEvent until one of the node's returns true.
- If every node returns false, the gesture is ignored and subsequent events that are part of the gesture will not be passed to any nodes.
- If one of the node's returns true, then that node will receive all future touch events for the gesture.

## Constructors

| | |
|---|---|
| [TouchEventSystem](-touch-event-system.md) | [androidJvm]<br>open fun [TouchEventSystem](-touch-event-system.md)() |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>open fun [onTouchEvent](on-touch-event.md)(pickHitResult: [PickHitResult](../-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |

## Properties

| Name | Summary |
|---|---|
| [onPeekTouchListener](on-peek-touch-listener.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [onPeekTouchListener](on-peek-touch-listener.md): ([PickHitResult](../-pick-hit-result/index.md), [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTouchListener](on-touch-listener.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [onTouchListener](on-touch-listener.md): ([PickHitResult](../-pick-hit-result/index.md), [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html) |
