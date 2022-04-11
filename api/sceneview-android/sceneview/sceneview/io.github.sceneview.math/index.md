//[sceneview](../../index.md)/[io.github.sceneview.math](index.md)

# Package io.github.sceneview.math

## Types

| Name | Summary |
|---|---|
| [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Position](index.md#945960193%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Position](index.md#945960193%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Size](index.md#1872733609%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Size](index.md#1872733609%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) = [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md) |

## Functions

| Name | Summary |
|---|---|
| [lerp](lerp.md) | [androidJvm]<br>fun [lerp](lerp.md)(a: [Float3](../dev.romainguy.kotlin.math/-float3/index.md), b: [Float3](../dev.romainguy.kotlin.math/-float3/index.md), t: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toColumnsFloatArray](to-columns-float-array.md) | [androidJvm]<br>fun [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md).[toColumnsFloatArray](to-columns-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toDirection](to-direction.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toDirection](to-direction.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toFloat3](to-float3.md) | [androidJvm]<br>fun [Vector3](../com.google.ar.sceneform.math/-vector3/index.md).[toFloat3](to-float3.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md)<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat3](to-float3.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toFloat4](to-float4.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat4](to-float4.md)(): [Float4](../dev.romainguy.kotlin.math/-float4/index.md) |
| [toLinearSpace](to-linear-space.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toLinearSpace](to-linear-space.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)<br>If rendering in linear space, first convert the values to linear space by rising to the power 2.2 |
| [toNewQuaternion](to-new-quaternion.md) | [androidJvm]<br>fun [Quaternion](../com.google.ar.sceneform.math/-quaternion/index.md).[toNewQuaternion](to-new-quaternion.md)(): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) |
| [toOldQuaternion](to-old-quaternion.md) | [androidJvm]<br>fun [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md).[toOldQuaternion](to-old-quaternion.md)(): [Quaternion](../com.google.ar.sceneform.math/-quaternion/index.md) |
| [toPosition](to-position.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toPosition](to-position.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toQuaternion](to-quaternion.md) | [androidJvm]<br>fun [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623).[toQuaternion](to-quaternion.md)(order: [RotationsOrder](../dev.romainguy.kotlin.math/-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) |
| [toRotation](to-rotation.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toRotation](to-rotation.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md)<br>fun [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md).[toRotation](to-rotation.md)(order: [RotationsOrder](../dev.romainguy.kotlin.math/-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toScale](to-scale.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toScale](to-scale.md)(): [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [toVector3](to-vector3.md) | [androidJvm]<br>fun [Float3](../dev.romainguy.kotlin.math/-float3/index.md).[toVector3](to-vector3.md)(): [Vector3](../com.google.ar.sceneform.math/-vector3/index.md) |
