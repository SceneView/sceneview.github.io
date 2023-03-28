//[sceneview](../../../index.md)/[com.google.ar.sceneform.collision](../index.md)/[Box](index.md)

# Box

[androidJvm]\
open class [Box](index.md) : [CollisionShape](../-collision-shape/index.md)

Mathematical representation of a box. Used to perform intersection and collision tests against oriented boxes.

## Constructors

| | |
|---|---|
| [Box](-box.md) | [androidJvm]<br>open fun [Box](-box.md)()<br>Create a box with a center of (0,0,0) and a size of (1,1,1). |
| [Box](-box.md) | [androidJvm]<br>open fun [Box](-box.md)(size: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md))<br>Create a box with a center of (0,0,0) and a specified size. |
| [Box](-box.md) | [androidJvm]<br>open fun [Box](-box.md)(size: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), center: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md))<br>Create a box with a specified center and size. |

## Functions

| Name | Summary |
|---|---|
| [getExtents](get-extents.md) | [androidJvm]<br>open fun [getExtents](get-extents.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Calculate the extents (half the size) of the box. |
| [getRotation](get-rotation.md) | [androidJvm]<br>open fun [getRotation](get-rotation.md)(): [Quaternion](../../com.google.ar.sceneform.math/-quaternion/index.md)<br>Get a copy of the box's rotation. |
| [makeCopy](make-copy.md) | [androidJvm]<br>open fun [makeCopy](make-copy.md)(): [Box](index.md) |
| [setRotation](set-rotation.md) | [androidJvm]<br>open fun [setRotation](set-rotation.md)(rotation: [Quaternion](../../com.google.ar.sceneform.math/-quaternion/index.md))<br>Set the rotation of this box. |

## Properties

| Name | Summary |
|---|---|
| [center](center.md) | [androidJvm]<br>var [center](center.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [size](size.md) | [androidJvm]<br>var [size](size.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
