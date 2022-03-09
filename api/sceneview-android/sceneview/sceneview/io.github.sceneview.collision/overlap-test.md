//[sceneview](../../index.md)/[io.github.sceneview.collision](index.md)/[overlapTest](overlap-test.md)

# overlapTest

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[overlapTest](overlap-test.md)(node: [Node](../io.github.sceneview.node/-node/index.md)): [Node](../io.github.sceneview.node/-node/index.md)?

Tests to see if the given node's collision shape overlaps the collision shape of any other nodes in the scene using Node.getCollisionShape. The node used for testing does not need to be active.

#### Return

A node that is overlapping the test node. If no node is overlapping the test node, then this is null. If multiple nodes are overlapping the test node, then this could be any of them.

## Parameters

androidJvm

| | |
|---|---|
| node | The node to use for the test. |
