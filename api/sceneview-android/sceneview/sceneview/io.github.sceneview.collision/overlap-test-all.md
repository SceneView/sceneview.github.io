//[sceneview](../../index.md)/[io.github.sceneview.collision](index.md)/[overlapTestAll](overlap-test-all.md)

# overlapTestAll

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[overlapTestAll](overlap-test-all.md)(node: [Node](../io.github.sceneview.node/-node/index.md)): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[Node](../io.github.sceneview.node/-node/index.md)&gt;

Tests to see if a node is overlapping any other nodes within the scene using Node.getCollisionShape. The node used for testing does not need to be active.

#### Return

A list of all nodes that are overlapping the test node. If no node is overlapping the test node, then the list is empty.

## Parameters

androidJvm

| | |
|---|---|
| node | The node to use for the test. |
