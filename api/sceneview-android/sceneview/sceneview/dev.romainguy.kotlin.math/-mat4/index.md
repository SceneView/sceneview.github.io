//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Mat4](index.md)

# Mat4

[androidJvm]\
data class [Mat4](index.md)(var x: [Float4](../-float4/index.md) = Float4(x = 1.0f), var y: [Float4](../-float4/index.md) = Float4(y = 1.0f), var z: [Float4](../-float4/index.md) = Float4(z = 1.0f), var w: [Float4](../-float4/index.md) = Float4(w = 1.0f))

## Constructors

| | |
|---|---|
| [Mat4](-mat4.md) | [androidJvm]<br>fun [Mat4](-mat4.md)(right: [Float3](../-float3/index.md), up: [Float3](../-float3/index.md), forward: [Float3](../-float3/index.md), position: [Float3](../-float3/index.md) = Float3()) |
| [Mat4](-mat4.md) | [androidJvm]<br>fun [Mat4](-mat4.md)(m: [Mat4](index.md)) |
| [Mat4](-mat4.md) | [androidJvm]<br>fun [Mat4](-mat4.md)(x: [Float4](../-float4/index.md) = Float4(x = 1.0f), y: [Float4](../-float4/index.md) = Float4(y = 1.0f), z: [Float4](../-float4/index.md) = Float4(z = 1.0f), w: [Float4](../-float4/index.md) = Float4(w = 1.0f)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [dec](dec.md) | [androidJvm]<br>operator fun [dec](dec.md)(): [Mat4](index.md) |
| [div](div.md) | [androidJvm]<br>operator fun [div](div.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat4](index.md) |
| [get](get.md) | [androidJvm]<br>operator fun [get](get.md)(column: [MatrixColumn](../-matrix-column/index.md)): [Float4](../-float4/index.md)<br>operator fun [get](get.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float4](../-float4/index.md)<br>operator fun [get](get.md)(column: [MatrixColumn](../-matrix-column/index.md), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [get](get.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [inc](inc.md) | [androidJvm]<br>operator fun [inc](inc.md)(): [Mat4](index.md) |
| [invoke](invoke.md) | [androidJvm]<br>operator fun [invoke](invoke.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [invoke](invoke.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [minus](minus.md) | [androidJvm]<br>operator fun [minus](minus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat4](index.md) |
| [plus](plus.md) | [androidJvm]<br>operator fun [plus](plus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat4](index.md) |
| [set](set.md) | [androidJvm]<br>operator fun [set](set.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float4](../-float4/index.md))<br>operator fun [set](set.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [times](times.md) | [androidJvm]<br>operator fun [times](times.md)(v: [Float4](../-float4/index.md)): [Float4](../-float4/index.md)<br>operator fun [times](times.md)(m: [Mat4](index.md)): [Mat4](index.md)<br>operator fun [times](times.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat4](index.md) |
| [toEulerAngles](to-euler-angles.md) | [androidJvm]<br>fun [toEulerAngles](to-euler-angles.md)(order: [RotationsOrder](../-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](../-float3/index.md)<br>Get the Euler angles in degrees from this rotation Matrix |
| [toFloatArray](to-float-array.md) | [androidJvm]<br>fun [toFloatArray](to-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toQuaternion](to-quaternion.md) | [androidJvm]<br>fun [toQuaternion](to-quaternion.md)(): [Quaternion](../-quaternion/index.md)<br>Get the [Quaternion](../-quaternion/index.md) from this rotation Matrix |
| [toString](to-string.md) | [androidJvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Mat4](index.md) |

## Properties

| Name | Summary |
|---|---|
| [forward](forward.md) | [androidJvm]<br>var [forward](forward.md): [Float3](../-float3/index.md) |
| [position](position.md) | [androidJvm]<br>var [position](position.md): [Float3](../-float3/index.md) |
| [right](right.md) | [androidJvm]<br>var [right](right.md): [Float3](../-float3/index.md) |
| [rotation](rotation.md) | [androidJvm]<br>val [rotation](rotation.md): [Float3](../-float3/index.md) |
| [scale](scale.md) | [androidJvm]<br>val [scale](scale.md): [Float3](../-float3/index.md) |
| [translation](translation.md) | [androidJvm]<br>val [translation](translation.md): [Float3](../-float3/index.md) |
| [up](up.md) | [androidJvm]<br>var [up](up.md): [Float3](../-float3/index.md) |
| [upperLeft](upper-left.md) | [androidJvm]<br>val [upperLeft](upper-left.md): [Mat3](../-mat3/index.md) |
| [w](w.md) | [androidJvm]<br>var [w](w.md): [Float4](../-float4/index.md) |
| [x](x.md) | [androidJvm]<br>var [x](x.md): [Float4](../-float4/index.md) |
| [y](y.md) | [androidJvm]<br>var [y](y.md): [Float4](../-float4/index.md) |
| [z](z.md) | [androidJvm]<br>var [z](z.md): [Float4](../-float4/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [equalsWithDelta](../../io.github.sceneview.math/equals-with-delta.md) | [androidJvm]<br>fun [Mat4](index.md).[equalsWithDelta](../../io.github.sceneview.math/equals-with-delta.md)(m: [Mat4](index.md), delta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = DEFAULT_EPSILON): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [quaternion](../../io.github.sceneview.math/quaternion.md) | [androidJvm]<br>val [Mat4](index.md).[quaternion](../../io.github.sceneview.math/quaternion.md): [Quaternion](../-quaternion/index.md) |
| [toColumnsFloatArray](../../io.github.sceneview.math/to-columns-float-array.md) | [androidJvm]<br>fun [Mat4](index.md).[toColumnsFloatArray](../../io.github.sceneview.math/to-columns-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
