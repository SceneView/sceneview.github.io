//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[onTouch](on-touch.md)

# onTouch

[androidJvm]\
open fun [onTouch](on-touch.md)(selectedNode: [Node](../../io.github.sceneview.node/-node/index.md)?, motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

[androidJvm]\
var [onTouch](on-touch.md): (selectedNode: [Node](../../io.github.sceneview.node/-node/index.md)?, motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null

###  Register a callback to be invoked on the surface singleTap

Called even if the touch is not over a selectable node, in which case node will be null.

- 
   selectedNode - The node that was hit by the hit test. Null when there is no hit
- 
   motionEvent - The original [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)
