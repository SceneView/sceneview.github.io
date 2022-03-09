//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[eulerAngles](euler-angles.md)

# eulerAngles

[androidJvm]\
fun [eulerAngles](euler-angles.md)(m: [Mat4](-mat4/index.md), order: [RotationsOrder](-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](-float3/index.md)

Get the Euler angles in degrees from a rotation Matrix

## Parameters

androidJvm

| | |
|---|---|
| m | The rotation matrix. Don't forget to extract the rotation with [rotation](rotation.md) if it's transposed |
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |

[androidJvm]\
fun [eulerAngles](euler-angles.md)(q: [Quaternion](-quaternion/index.md), order: [RotationsOrder](-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](-float3/index.md)

Convert a Quaternion to Euler angles

## Parameters

androidJvm

| | |
|---|---|
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |
