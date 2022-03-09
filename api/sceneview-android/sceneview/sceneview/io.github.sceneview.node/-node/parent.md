//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[parent](parent.md)

# parent

[androidJvm]\
var [parent](parent.md): [NodeParent](../-node-parent/index.md)? = null

###  Changes the parent node of this node

If set to null, this node will be detached ([removeChild](../../../../sceneview/io.github.sceneview.node/-node/remove-child.md)) from its parent.

The parent may be another [Node](index.md) or a [SceneView](../../io.github.sceneview/-scene-view/index.md). If it is a scene, then this [Node](index.md) is considered top level.

The local position, rotation, and scale of this node will remain the same. Therefore, the world position, rotation, and scale of this node may be different after the parent changes.

In addition to setting this field, setParent will also do the following things:

- 
   Remove this node from its previous parent's children.
- 
   Add this node to its new parent's children.
- 
   Recursively update the node's transformation to reflect the change in parent -Recursively update the scene field to match the new parent's scene field.
