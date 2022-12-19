//[sceneview](../../index.md)/[io.github.sceneview.math](index.md)

# Package io.github.sceneview.math

## Types

| Name | Summary |
|---|---|
| [Axis](index.md#-272535031%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Axis](index.md#-272535031%2FClasslikes%2F-1571379623) = VectorComponent |
| [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Direction](index.md#1758682841%2FClasslikes%2F-1571379623) = Float3 |
| [LookAt](-look-at/index.md) | [androidJvm]<br>data class [LookAt](-look-at/index.md)(val eye: [Position](index.md#945960193%2FClasslikes%2F-1571379623), val target: [Position](index.md#945960193%2FClasslikes%2F-1571379623), val upward: [Direction](index.md#1758682841%2FClasslikes%2F-1571379623)) |
| [Position](index.md#945960193%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Position](index.md#945960193%2FClasslikes%2F-1571379623) = Float3 |
| [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623) = Float3 |
| [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Scale](index.md#2055938798%2FClasslikes%2F-1571379623) = Float3 |
| [Size](index.md#1872733609%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Size](index.md#1872733609%2FClasslikes%2F-1571379623) = Float3 |
| [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Transform](index.md#1875660684%2FClasslikes%2F-1571379623) = Mat4 |

## Functions

| Name | Summary |
|---|---|
| [Box](-box.md) | [androidJvm]<br>fun [Box](-box.md)(center: [Position](index.md#945960193%2FClasslikes%2F-1571379623), halfExtent: [Size](index.md#1872733609%2FClasslikes%2F-1571379623)): Box |
| [lookAt](look-at.md) | [androidJvm]<br>fun [lookAt](look-at.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-1571379623), target: [Position](index.md#945960193%2FClasslikes%2F-1571379623)): Mat4 |
| [lookTowards](look-towards.md) | [androidJvm]<br>fun [lookTowards](look-towards.md)(eye: [Position](index.md#945960193%2FClasslikes%2F-1571379623), direction: [Direction](index.md#1758682841%2FClasslikes%2F-1571379623)): Quaternion |
| [max](max.md) | [androidJvm]<br>fun [max](max.md)(a: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Float3&gt;): Float3 |
| [min](min.md) | [androidJvm]<br>fun [min](min.md)(a: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Float3&gt;): Float3 |
| [normalToTangent](normal-to-tangent.md) | [androidJvm]<br>fun [normalToTangent](normal-to-tangent.md)(normal: Float3): Quaternion |
| [times](times.md) | [androidJvm]<br>operator fun Mat4.[times](times.md)(v: Float3): Float3 |
| [toColumnsFloatArray](to-columns-float-array.md) | [androidJvm]<br>fun Mat4.[toColumnsFloatArray](to-columns-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toDirection](to-direction.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toDirection](to-direction.md)(): Float3 |
| [toDoubleArray](to-double-array.md) | [androidJvm]<br>fun Mat4.[toDoubleArray](to-double-array.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [toFloat3](to-float3.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat3](to-float3.md)(): Float3 |
| [toFloat4](to-float4.md) | [androidJvm]<br>fun [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html).[toFloat4](to-float4.md)(): Float4<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toFloat4](to-float4.md)(): Float4 |
| [toLinearSpace](to-linear-space.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toLinearSpace](to-linear-space.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)<br>If rendering in linear space, first convert the values to linear space by rising to the power 2.2 |
| [toPosition](to-position.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toPosition](to-position.md)(): Float3 |
| [toQuaternion](to-quaternion.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toQuaternion](to-quaternion.md)(): Quaternion<br>fun [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623).[toQuaternion](to-quaternion.md)(order: RotationsOrder = RotationsOrder.ZYX): Quaternion |
| [toRotation](to-rotation.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toRotation](to-rotation.md)(): Float3<br>fun Quaternion.[toRotation](to-rotation.md)(order: RotationsOrder = RotationsOrder.ZYX): Float3 |
| [toScale](to-scale.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toScale](to-scale.md)(): Float3 |
| [toSize](to-size.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toSize](to-size.md)(): Float3 |
| [toTransform](to-transform.md) | [androidJvm]<br>fun [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html).[toTransform](to-transform.md)(): Mat4<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toTransform](to-transform.md)(): Mat4 |
| [Transform](-transform.md) | [androidJvm]<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-1571379623), rotation: [Rotation](index.md#1133844556%2FClasslikes%2F-1571379623), scale: [Scale](index.md#2055938798%2FClasslikes%2F-1571379623)): Mat4<br>fun [Transform](-transform.md)(position: [Position](index.md#945960193%2FClasslikes%2F-1571379623), quaternion: Quaternion, scale: [Scale](index.md#2055938798%2FClasslikes%2F-1571379623)): Mat4 |

## Properties

| Name | Summary |
|---|---|
| [centerPosition](center-position.md) | [androidJvm]<br>var Box.[centerPosition](center-position.md): [Position](index.md#945960193%2FClasslikes%2F-1571379623) |
| [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md) | [androidJvm]<br>const val [DEFAULT_EPSILON](-d-e-f-a-u-l-t_-e-p-s-i-l-o-n.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.001f |
| [halfExtentSize](half-extent-size.md) | [androidJvm]<br>var Box.[halfExtentSize](half-extent-size.md): [Size](index.md#1872733609%2FClasslikes%2F-1571379623) |
| [quaternion](quaternion.md) | [androidJvm]<br>val Mat4.[quaternion](quaternion.md): Quaternion |
| [size](size.md) | [androidJvm]<br>var Box.[size](size.md): Float3 |
