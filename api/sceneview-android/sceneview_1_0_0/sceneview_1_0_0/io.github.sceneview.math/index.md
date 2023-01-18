//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.math](index.md)

# Package io.github.sceneview.math

## Types

| Name | Summary |
|---|---|
| [Axis](index.md#-272535031%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Axis](index.md#-272535031%2FClasslikes%2F-602047187) = [VectorComponent](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-vector-component/index.md) |
| [Direction](index.md#1758682841%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Direction](index.md#1758682841%2FClasslikes%2F-602047187) = [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [LookAt](-look-at/index.md) | [androidJvm]<br>data class [LookAt](-look-at/index.md)(val eye: [Position](index.md#945960193%2FClasslikes%2F-602047187), val target: [Position](index.md#945960193%2FClasslikes%2F-602047187), val upward: [Direction](index.md#1758682841%2FClasslikes%2F-602047187)) |
| [Position](index.md#945960193%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Position](index.md#945960193%2FClasslikes%2F-602047187) = [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [Rotation](index.md#1133844556%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Rotation](index.md#1133844556%2FClasslikes%2F-602047187) = [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [Scale](index.md#2055938798%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Scale](index.md#2055938798%2FClasslikes%2F-602047187) = [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [Size](index.md#1872733609%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Size](index.md#1872733609%2FClasslikes%2F-602047187) = [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [Transform](index.md#1875660684%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Transform](index.md#1875660684%2FClasslikes%2F-602047187) = [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md) |

## Functions

| Name | Summary |
|---|---|
| [Box](-box.md) | [androidJvm]<br>fun [Box](-box.md)(center: [Position](index.md#945960193%2FClasslikes%2F-602047187), halfExtent: [Size](index.md#1872733609%2FClasslikes%2F-602047187)): Box |
| [lookAt](look-at.md) | [androidJvm]<br>fun [lookAt](look-at.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-602047187), target: [Position](index.md#945960193%2FClasslikes%2F-602047187)): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md) |
| [lookTowards](look-towards.md) | [androidJvm]<br>fun [lookTowards](look-towards.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-602047187), direction: [Direction](index.md#1758682841%2FClasslikes%2F-602047187)): [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md) |
| [max](max.md) | [androidJvm]<br>fun [max](max.md)(a: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)&gt;): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [min](min.md) | [androidJvm]<br>fun [min](min.md)(a: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)&gt;): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [normalToTangent](normal-to-tangent.md) | [androidJvm]<br>fun [normalToTangent](normal-to-tangent.md)(normal: [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)): [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md) |
| [times](times.md) | [androidJvm]<br>operator fun [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md).[times](times.md)(v: [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toColumnsFloatArray](to-columns-float-array.md) | [androidJvm]<br>fun [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md).[toColumnsFloatArray](to-columns-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toDirection](to-direction.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toDirection](to-direction.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toDoubleArray](to-double-array.md) | [androidJvm]<br>fun [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md).[toDoubleArray](to-double-array.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [toFloat3](to-float3.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat3](to-float3.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toFloat4](to-float4.md) | [androidJvm]<br>fun [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html).[toFloat4](to-float4.md)(): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat4](to-float4.md)(): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |
| [toLinearSpace](to-linear-space.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toLinearSpace](to-linear-space.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)<br>If rendering in linear space, first convert the values to linear space by rising to the power 2.2 |
| [toPosition](to-position.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toPosition](to-position.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toQuaternion](to-quaternion.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toQuaternion](to-quaternion.md)(): [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md)<br>fun [Rotation](index.md#1133844556%2FClasslikes%2F-602047187).[toQuaternion](to-quaternion.md)(order: [RotationsOrder](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-rotations-order/index.md) = RotationsOrder.ZYX): [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md) |
| [toRotation](to-rotation.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toRotation](to-rotation.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)<br>fun [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md).[toRotation](to-rotation.md)(order: [RotationsOrder](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toScale](to-scale.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toScale](to-scale.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toSize](to-size.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toSize](to-size.md)(): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [toTransform](to-transform.md) | [androidJvm]<br>fun [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html).[toTransform](to-transform.md)(): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md)<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toTransform](to-transform.md)(): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md) |
| [Transform](-transform.md) | [androidJvm]<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-602047187), rotation: [Rotation](index.md#1133844556%2FClasslikes%2F-602047187), scale: [Scale](index.md#2055938798%2FClasslikes%2F-602047187)): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md)<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-602047187), quaternion: [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md), scale: [Scale](index.md#2055938798%2FClasslikes%2F-602047187)): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md) |

## Properties

| Name | Summary |
|---|---|
| [centerPosition](center-position.md) | [androidJvm]<br>var Box.[centerPosition](center-position.md): [Position](index.md#945960193%2FClasslikes%2F-602047187) |
| [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md) | [androidJvm]<br>const val [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.001f |
| [halfExtentSize](half-extent-size.md) | [androidJvm]<br>var Box.[halfExtentSize](half-extent-size.md): [Size](index.md#1872733609%2FClasslikes%2F-602047187) |
| [quaternion](quaternion.md) | [androidJvm]<br>val [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md).[quaternion](quaternion.md): [Quaternion](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md) |
| [size](size.md) | [androidJvm]<br>var Box.[size](size.md): [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
