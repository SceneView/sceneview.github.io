//[sceneview](../../../../index.md)/[dev.romainguy.kotlin.math](../../index.md)/[Quaternion](../index.md)/[Companion](index.md)/[fromEuler](from-euler.md)

# fromEuler

[androidJvm]\
fun [fromEuler](from-euler.md)(d: [Float3](../../-float3/index.md), order: [RotationsOrder](../../-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../index.md)

Construct a Quaternion from Euler angles using YPR around a specified order

Uses intrinsic Tait-Bryan angles. This means that rotations are performed with respect to the local coordinate system. That is, for order 'XYZ', the rotation is first around the X axis (which is the same as the world-X axis), then around local-Y (which may now be different from the world Y-axis), then local-Z (which may be different from the world Z-axis)

## Parameters

androidJvm

| | |
|---|---|
| d | Per axis Euler angles in degrees Yaw, pitch, roll (YPR) are taken accordingly to the rotations order input. |
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](../../-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |

[androidJvm]\
fun [fromEuler](from-euler.md)(yaw: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, pitch: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, roll: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, order: [RotationsOrder](../../-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../index.md)

Construct a Quaternion from Euler yaw, pitch, roll around a specified order.

## Parameters

androidJvm

| | |
|---|---|
| roll | about 1st rotation axis in radians. Z in case of ZYX order |
| pitch | about 2nd rotation axis in radians. Y in case of ZYX order |
| yaw | about 3rd rotation axis in radians. X in case of ZYX order |
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](../../-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |
