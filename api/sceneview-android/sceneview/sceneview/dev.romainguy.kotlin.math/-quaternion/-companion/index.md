//[sceneview](../../../../index.md)/[dev.romainguy.kotlin.math](../../index.md)/[Quaternion](../index.md)/[Companion](index.md)

# Companion

[androidJvm]\
object [Companion](index.md)

## Functions

| Name | Summary |
|---|---|
| [fromAxisAngle](from-axis-angle.md) | [androidJvm]<br>fun [fromAxisAngle](from-axis-angle.md)(axis: [Float3](../../-float3/index.md), angle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](../index.md)<br>Construct a Quaternion from an axis and angle in degrees |
| [fromEuler](from-euler.md) | [androidJvm]<br>fun [fromEuler](from-euler.md)(d: [Float3](../../-float3/index.md), order: [RotationsOrder](../../-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../index.md)<br>Construct a Quaternion from Euler angles using YPR around a specified order<br>[androidJvm]<br>fun [fromEuler](from-euler.md)(yaw: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, pitch: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, roll: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, order: [RotationsOrder](../../-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../index.md)<br>Construct a Quaternion from Euler yaw, pitch, roll around a specified order. |
