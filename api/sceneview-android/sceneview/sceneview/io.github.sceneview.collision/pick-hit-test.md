//[sceneview](../../index.md)/[io.github.sceneview.collision](index.md)/[pickHitTest](pick-hit-test.md)

# pickHitTest

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTest](pick-hit-test.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), focusableOnly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)

Tests to see if a motion event is touching any nodes within the scene, based on a ray hit test whose origin is the screen position of the motion event, and outputs a PickHitResult containing the node closest to the screen.

#### Return

the result includes the first node that was hit by the motion event (may be null), and information about where the motion event hit the node in world-space

## Parameters

androidJvm

| | |
|---|---|
| motionEvent | the motion event to use for the test |
| focusableOnly | Filter the PickHitResult on only selectable nodes |

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTest](pick-hit-test.md)(ray: [Ray](../com.google.ar.sceneform.collision/-ray/index.md), selectableOnly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)

Tests to see if a ray is hitting any nodes within the scene and outputs a PickHitResult containing the node closest to the ray origin that intersects with the ray.

#### Return

the result includes the first node that was hit by the ray (may be null), and information about where the ray hit the node in world-space

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.CameraNode](../../../arsceneview/com.google.ar.sceneform/-camera-node/screen-point-to-ray.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| ray | the ray to use for the test |
| selectableOnly | Filter the PickHitResult on only selectable nodes |
