//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ViewNode](index.md)/[dispatchTouchEvent](dispatch-touch-event.md)

# dispatchTouchEvent

[androidJvm]\
open override fun [dispatchTouchEvent](dispatch-touch-event.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Calls onTouchEvent if the node is active

Used by TouchEventSystem to dispatch touch events.

#### Return

true if the event was handled, false otherwise.

## Parameters

androidJvm

| | |
|---|---|
| pickHitResult | Represents the node that was touched, and information about where it was touched. On ACTION_DOWN events, [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) will always be this node or one of its children. On other events, the touch may have moved causing the [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) to change (or possibly be null). |
| motionEvent | The motion event. |
