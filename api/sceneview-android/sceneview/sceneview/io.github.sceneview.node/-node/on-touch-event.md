//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[onTouchEvent](on-touch-event.md)

# onTouchEvent

[androidJvm]\
fun [onTouchEvent](on-touch-event.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Handles when this node is touched

Override to perform any logic that should occur when this node is touched. The way that touch events are propagated mirrors the way touches are propagated to Android Views. This is only called when the node is active.

When an ACTION_DOWN event occurs, that represents the start of a gesture. ACTION_UP or ACTION_CANCEL represents when a gesture ends. When a gesture starts, the following is done:

- 
   Dispatch touch events to the node that was touched as detected by hitTest.
- 
   If the node doesn't consume the event, recurse upwards through the node's parents and dispatch the touch event until one of the node's consumes the event.
- 
   If no nodes consume the event, the gesture is ignored and subsequent events that are part of the gesture will not be passed to any nodes.
- 
   If one of the node's consumes the event, then that node will consume all future touch events for the gesture.

When a touch event is dispatched to a node, the event is first passed to the node's. If the [onTouchEvent](on-touch-event.md) doesn't handle the event, it is passed to [onTouchEvent](on-touch-event.md).

#### Return

true if the event was handled, false otherwise.

## Parameters

androidJvm

| | |
|---|---|
| pickHitResult | Represents the node that was touched, and information about where it was touched. On ACTION_DOWN events, [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) will always be this node or one of its children. On other events, the touch may have moved causing the [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) to change (or possibly be null). |
| motionEvent | The motion event. |

[androidJvm]\
var [onTouchEvent](on-touch-event.md): (pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null

###  Registers a callback to be invoked when a touch event is dispatched to this node

The way that touch events are propagated mirrors the way touches are propagated to Android Views. This is only called when the node is active.

When an ACTION_DOWN event occurs, that represents the start of a gesture. ACTION_UP or ACTION_CANCEL represents when a gesture ends. When a gesture starts, the following is done:

- 
   Dispatch touch events to the node that was touched as detected by hitTest.
- 
   If the node doesn't consume the event, recurse upwards through the node's parents and dispatch the touch event until one of the node's consumes the event.
- 
   If no nodes consume the event, the gesture is ignored and subsequent events that are part of the gesture will not be passed to any nodes.
- 
   If one of the node's consumes the event, then that node will consume all future touch events for the gesture.

When a touch event is dispatched to a node, the event is first passed to the node's. If the [onTouchEvent](on-touch-event.md) doesn't handle the event, it is passed to .onTouchEvent.

- 
   pickHitResult - Represents the node that was touched and information about where it was touched
- 
   motionEvent - The MotionEvent object containing full information about the event
- 
   return true if the listener has consumed the event, false otherwise
