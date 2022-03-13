//[sceneview](../../index.md)/[io.github.sceneview.collision](index.md)

# Package io.github.sceneview.collision

## Functions

| Name | Summary |
|---|---|
| [overlapTest](overlap-test.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[overlapTest](overlap-test.md)(node: [Node](../io.github.sceneview.node/-node/index.md)): [Node](../io.github.sceneview.node/-node/index.md)?<br>Tests to see if the given node's collision shape overlaps the collision shape of any other nodes in the scene using Node.getCollisionShape. The node used for testing does not need to be active. |
| [overlapTestAll](overlap-test-all.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[overlapTestAll](overlap-test-all.md)(node: [Node](../io.github.sceneview.node/-node/index.md)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[Node](../io.github.sceneview.node/-node/index.md)&gt;<br>Tests to see if a node is overlapping any other nodes within the scene using Node.getCollisionShape. The node used for testing does not need to be active. |
| [pickHitTest](pick-hit-test.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTest](pick-hit-test.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), focusableOnly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)<br>Tests to see if a motion event is touching any nodes within the scene, based on a ray hit test whose origin is the screen position of the motion event, and outputs a PickHitResult containing the node closest to the screen.<br>[androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTest](pick-hit-test.md)(ray: [Ray](../com.google.ar.sceneform.collision/-ray/index.md), focusableOnly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)<br>Tests to see if a ray is hitting any nodes within the scene and outputs a PickHitResult containing the node closest to the ray origin that intersects with the ray. |
| [pickHitTests](pick-hit-tests.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTests](pick-hit-tests.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)&gt;<br>Tests to see if a motion event is touching any nodes within the scene and returns a list of HitTestResults containing all of the nodes that were hit, sorted by distance.<br>[androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[pickHitTests](pick-hit-tests.md)(ray: [Ray](../com.google.ar.sceneform.collision/-ray/index.md)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[PickHitResult](../com.google.ar.sceneform/-pick-hit-result/index.md)&gt;<br>Tests to see if a ray is hitting any nodes within the scene and returns a list of HitTestResults containing all of the nodes that were hit, sorted by distance. |