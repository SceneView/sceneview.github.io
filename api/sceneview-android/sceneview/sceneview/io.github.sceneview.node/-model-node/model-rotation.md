//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[modelRotation](model-rotation.md)

# modelRotation

[androidJvm]\
open var [modelRotation](model-rotation.md): [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623)

###  The node model orientation

A node's content origin is the transformation between its coordinate space and that used by its [quaternion](../../dev.romainguy.kotlin.math/quaternion.md). The default origin is zero vector, specifying that the node's orientation locates the origin of its rotation relatively to that center point.

`[0..360]`

Changing the origin transform alters these behaviors in many useful ways. You can move the node's axis of rotation. For example, with a translation transform you can cause a node to revolve around a faraway point instead of rotating around its center, and with a rotation transform you can tilt the axis of rotation.
