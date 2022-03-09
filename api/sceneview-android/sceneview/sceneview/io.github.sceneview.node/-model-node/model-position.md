//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[modelPosition](model-position.md)

# modelPosition

[androidJvm]\
open var [modelPosition](model-position.md): [Float3](../../dev.romainguy.kotlin.math/-float3/index.md)

###  The node model origin (center)

A node's content origin is the transformation between its coordinate space and that used by its [position](../../../../sceneview/io.github.sceneview.node/-model-node/position.md). The default origin is zero vector, specifying that the node's position locates the origin of its coordinate system relatively to that center point.

Changing the origin transform alters these behaviors in many useful ways. You can offset the node's contents relative to its position. For example, by setting the pivot to a translation transform you can position a node containing a sphere geometry relative to where the sphere would rest on a floor instead of relative to its center.
