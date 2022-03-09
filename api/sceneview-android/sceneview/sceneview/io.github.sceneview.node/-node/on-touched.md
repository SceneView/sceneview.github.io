//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[onTouched](on-touched.md)

# onTouched

[androidJvm]\
var [onTouched](on-touched.md): (pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Registers a callback to be invoked when this node is tapped.

If there is a callback registered, then touch events will not bubble to this node's parent. If the Node.onTouchEvent is overridden and super.onTouchEvent is not called, then the tap will not occur.

- 
   pickHitResult - represents the node that was tapped and information about where it was touched
- 
   `motionEvent - The [MotionEvent.ACTION_UP](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html#action_up) MotionEvent that caused the tap
