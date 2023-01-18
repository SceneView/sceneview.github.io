//[sceneview](../../index.md)/[io.github.sceneview.math](index.md)

# Package io.github.sceneview.math

## Types

| Name | Summary |
|---|---|
| [Axis](index.md#-272535031%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Axis](index.md#-272535031%2FClasslikes%2F-1571379623) = [VectorComponent](../dev.romainguy.kotlin.math/-vector-component/index.md) |
| [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Position](index.md#945960193%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Position](index.md#945960193%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Size](index.md#1872733609%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Size](index.md#1872733609%2FClasslikes%2F-1571379623) = [Float3](../dev.romainguy.kotlin.math/-float3/index.md) |
| [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) = [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md) |

## Functions

| Name | Summary |
|---|---|
| [lerp](lerp.md) | [androidJvm]<br>fun [lerp](lerp.md)(start: [Float3](../dev.romainguy.kotlin.math/-float3/index.md), end: [Float3](../dev.romainguy.kotlin.math/-float3/index.md), deltaSeconds: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), epsilon: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = DEFAULT_EPSILON): [Float3](../dev.romainguy.kotlin.math/-float3/index.md)<br>fun [lerp](lerp.md)(start: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md), end: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md), deltaSeconds: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), epsilon: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = DEFAULT_EPSILON): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) |
| [lookAt](look-at.md) | [androidJvm]<br>fun [lookAt](look-at.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-1571379623), target: [Position](index.md#945960193%2FClasslikes%2F-1571379623)): [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md) |
| [lookTowards](look-towards.md) | [androidJvm]<br>fun [lookTowards](look-towards.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-1571379623), direction: [Direction](index.md#1758682841%2FClasslikes%2F-1571379623)): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) |
| [slerp](slerp.md) | [androidJvm]<br>fun [slerp](slerp.md)(start: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md), end: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md), deltaSeconds: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), epsilon: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = DEFAULT_EPSILON): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md)<br>fun [slerp](slerp.md)(start: [Transform](index.md#1875660684%2FClasslikes%2F-1571379623), end: [Transform](index.md#1875660684%2FClasslikes%2F-1571379623), deltaSeconds: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), speed: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), epsilon: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = DEFAULT_EPSILON): [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) |
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
| [Transform](-transform.md) | [androidJvm]<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-1571379623), rotation: [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623), scale: [Scale](index.md#2055938798%2FClasslikes%2F-1571379623)): [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md)<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-1571379623), quaternion: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md), scale: [Scale](index.md#2055938798%2FClasslikes%2F-1571379623)): [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md) |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md) | [androidJvm]<br>const val [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.001f |
| [quaternion](quaternion.md) | [androidJvm]<br>val [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md).[quaternion](quaternion.md): [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) |
