//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Mat4](index.md)/[toEulerAngles](to-euler-angles.md)

# toEulerAngles

[androidJvm]\
fun [toEulerAngles](to-euler-angles.md)(order: [RotationsOrder](../-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](../-float3/index.md)

Get the Euler angles in degrees from this rotation Matrix

Don't forget to extract the rotation with [rotation](../rotation.md) if this is a transposed matrix

## See also

androidJvm

| | |
|---|---|
| [eulerAngles](../euler-angles.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](../-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |
