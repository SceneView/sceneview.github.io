//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[onTouchEvent](on-touch-event.md)

# onTouchEvent

[androidJvm]\
open override fun [onTouchEvent](on-touch-event.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

[androidJvm]\
open fun [onTouchEvent](on-touch-event.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

###  Invoked when the scene is touched.

Called even if the touch is not over a node, in which case [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) will be null.

## Parameters

androidJvm

| | |
|---|---|
| pickHitResult | represents the node that was touched |
| motionEvent | the motion event |

[androidJvm]\
var [onTouchEvent](on-touch-event.md): (pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null

###  Register a callback to be invoked when the scene is touched.

You should not use this callback in you have anything on your scene. Node selection, gestures recognizer and surface gesture recognizer won't be updated if you return true.

**Have a look at** [**onTouch**](on-touch.md) **or other gestures listeners**

Called even if the touch is not over a node, in which case [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) will be null.

- 
   pickHitResult - represents the node that was touched if any
- 
   motionEvent - the motion event
- 
   return true if the listener has consumed the event
