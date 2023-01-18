//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Quaternion](index.md)/[lookRotation](look-rotation.md)

# lookRotation

[androidJvm]\
open fun [lookRotation](look-rotation.md)(forwardInWorld: [Vector3](../-vector3/index.md), desiredUpInWorld: [Vector3](../-vector3/index.md)): [Quaternion](index.md)

Get a new Quaternion representing a rotation towards a specified forward direction. If upInWorld is orthogonal to forwardInWorld, then the Y axis is aligned with desiredUpInWorld.
