//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ViewRenderable](index.md)/[dispatchTouchEventToView](dispatch-touch-event-to-view.md)

# dispatchTouchEventToView

[androidJvm]\
open fun [dispatchTouchEventToView](dispatch-touch-event-to-view.md)(@NotNullnode: [Node](../../io.github.sceneview.node/-node/index.md), @NotNullmotionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Dispatches a touch event to a node's ViewRenderable if that node has a ViewRenderable by converting the touch event into the local coordinate space of the view.
