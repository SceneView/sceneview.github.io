//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Mat3](index.md)

# Mat3

[androidJvm]\
data class [Mat3](index.md)(var x: [Float3](../-float3/index.md) = Float3(x = 1.0f), var y: [Float3](../-float3/index.md) = Float3(y = 1.0f), var z: [Float3](../-float3/index.md) = Float3(z = 1.0f))

## Constructors

| | |
|---|---|
| [Mat3](-mat3.md) | [androidJvm]<br>fun [Mat3](-mat3.md)(m: [Mat3](index.md)) |
| [Mat3](-mat3.md) | [androidJvm]<br>fun [Mat3](-mat3.md)(x: [Float3](../-float3/index.md) = Float3(x = 1.0f), y: [Float3](../-float3/index.md) = Float3(y = 1.0f), z: [Float3](../-float3/index.md) = Float3(z = 1.0f)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [dec](dec.md) | [androidJvm]<br>operator fun [dec](dec.md)(): [Mat3](index.md) |
| [div](div.md) | [androidJvm]<br>operator fun [div](div.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat3](index.md) |
| [get](get.md) | [androidJvm]<br>operator fun [get](get.md)(column: [MatrixColumn](../-matrix-column/index.md)): [Float3](../-float3/index.md)<br>operator fun [get](get.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float3](../-float3/index.md)<br>operator fun [get](get.md)(column: [MatrixColumn](../-matrix-column/index.md), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [get](get.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [inc](inc.md) | [androidJvm]<br>operator fun [inc](inc.md)(): [Mat3](index.md) |
| [invoke](invoke.md) | [androidJvm]<br>operator fun [invoke](invoke.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [invoke](invoke.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [minus](minus.md) | [androidJvm]<br>operator fun [minus](minus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat3](index.md) |
| [plus](plus.md) | [androidJvm]<br>operator fun [plus](plus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat3](index.md) |
| [set](set.md) | [androidJvm]<br>operator fun [set](set.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float3](../-float3/index.md))<br>operator fun [set](set.md)(column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [times](times.md) | [androidJvm]<br>operator fun [times](times.md)(v: [Float3](../-float3/index.md)): [Float3](../-float3/index.md)<br>operator fun [times](times.md)(m: [Mat3](index.md)): [Mat3](index.md)<br>operator fun [times](times.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Mat3](index.md) |
| [toFloatArray](to-float-array.md) | [androidJvm]<br>fun [toFloatArray](to-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toString](to-string.md) | [androidJvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Mat3](index.md) |

## Properties

| Name | Summary |
|---|---|
| [x](x.md) | [androidJvm]<br>var [x](x.md): [Float3](../-float3/index.md) |
| [y](y.md) | [androidJvm]<br>var [y](y.md): [Float3](../-float3/index.md) |
| [z](z.md) | [androidJvm]<br>var [z](z.md): [Float3](../-float3/index.md) |
