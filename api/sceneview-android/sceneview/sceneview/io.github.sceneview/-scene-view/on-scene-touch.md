//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[onSceneTouch](on-scene-touch.md)

# onSceneTouch

[androidJvm]\
open fun [onSceneTouch](on-scene-touch.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

###  Invoked when the scene is touched.

Called even if the touch is not over a node, in which case [PickHitResult.getNode](../../../../arsceneview/com.google.ar.sceneform/-pick-hit-result/get-node.md) will be null.

## Parameters

androidJvm

| | |
|---|---|
| pickHitResult | represents the node that was touched |
| motionEvent | the motion event |
