//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[createAnchoredNode](create-anchored-node.md)

# createAnchoredNode

[androidJvm]\
open fun [createAnchoredNode](create-anchored-node.md)(): [ArNode](index.md)?

###  Creates a new anchored Node at the actual worldPosition and worldRotation

The returned node position and rotation will be fixed within camera movements.

See [ArFrame.hitTest](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) and [ArFrame.hitTests](../../io.github.sceneview.ar.arcore/-ar-frame/hit-tests.md) for details.

Anchors incur ongoing processing overhead within ARCore. To release unneeded anchors use [destroy](destroy.md).
