//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Quaternion](index.md)/[eulerAngles](euler-angles.md)

# eulerAngles

[androidJvm]\
open fun [eulerAngles](euler-angles.md)(eulerAngles: [Vector3](../-vector3/index.md)): [Quaternion](index.md)

Get a new Quaternion using eulerAngles to define the rotation. 

The rotations are applied in Z, Y, X order. This is consistent with other graphics engines. One thing to note is the coordinate systems are different between Sceneform and Unity, so the same angles used here will have cause a different orientation than Unity. Carefully check your parameter values to get the same effect as in other engines.

## Parameters

androidJvm

| | |
|---|---|
| eulerAngles | - the angles in degrees. |
