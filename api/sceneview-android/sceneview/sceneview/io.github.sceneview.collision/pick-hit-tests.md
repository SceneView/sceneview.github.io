//[sceneview](../../index.md)/[io.github.sceneview.collision](index.md)/[pickHitTests](pick-hit-tests.md)

# pickHitTests

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTests](pick-hit-tests.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)&gt;

Tests to see if a motion event is touching any nodes within the scene and returns a list of HitTestResults containing all of the nodes that were hit, sorted by distance.

#### Return

Populated with a PickHitResult for each node that was hit sorted by distance. Empty if no nodes were hit.

## Parameters

androidJvm

| | |
|---|---|
| motionEvent | The motion event to use for the test. |

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTests](pick-hit-tests.md)(ray: [Ray](../com.google.ar.sceneform.collision/-ray/index.md)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)&gt;

Tests to see if a ray is hitting any nodes within the scene and returns a list of HitTestResults containing all of the nodes that were hit, sorted by distance.

#### Return

Populated with a PickHitResult for each node that was hit sorted by distance. Empty if no nodes were hit.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.CameraNode](../../../arsceneview/com.google.ar.sceneform/-camera-node/screen-point-to-ray.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| ray | The ray to use for the test. |
