//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[rotation](rotation.md)

# rotation

[androidJvm]\
fun [rotation](rotation.md)(m: [Mat4](-mat4/index.md)): [Mat4](-mat4/index.md)

fun [rotation](rotation.md)(axis: [Float3](-float3/index.md), angle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat4](-mat4/index.md)

[androidJvm]\
fun [rotation](rotation.md)(d: [Float3](-float3/index.md), order: [RotationsOrder](-rotations-order/index.md) = RotationsOrder.ZYX): [Mat4](-mat4/index.md)

Construct a rotation matrix from Euler angles using YPR around a specified order

Uses intrinsic Tait-Bryan angles. This means that rotations are performed with respect to the local coordinate system. That is, for order 'XYZ', the rotation is first around the X axis (which is the same as the world-X axis), then around local-Y (which may now be different from the world Y-axis), then local-Z (which may be different from the world Z-axis)

#### Return

The rotation matrix

## Parameters

androidJvm

| | |
|---|---|
| d | Per axis Euler angles in degrees Yaw, pitch, roll (YPR) are taken accordingly to the rotations order input. |
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |

[androidJvm]\
fun [rotation](rotation.md)(yaw: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, pitch: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, roll: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, order: [RotationsOrder](-rotations-order/index.md) = RotationsOrder.ZYX): [Mat4](-mat4/index.md)

Construct a rotation matrix from Euler yaw, pitch, roll around a specified order.

#### Return

The rotation matrix

## Parameters

androidJvm

| | |
|---|---|
| roll | about 1st rotation axis in radians. Z in case of ZYX order |
| pitch | about 2nd rotation axis in radians. Y in case of ZYX order |
| yaw | about 3rd rotation axis in radians. X in case of ZYX order |
| order | The order in which to apply rotations. Default is [RotationsOrder.ZYX](-rotations-order/-z-y-x/index.md) which means that the object will first be rotated around its Z axis, then its Y axis and finally its X axis. |

[androidJvm]\
fun [rotation](rotation.md)(quaternion: [Quaternion](-quaternion/index.md)): [Mat4](-mat4/index.md)

Construct a Quaternion Rotation Matrix following the Hamilton convention

Assume the destination and local coordinate spaces are initially aligned, and the local coordinate space is then rotated counter-clockwise about a unit-length axis, k, by an angle, theta.
