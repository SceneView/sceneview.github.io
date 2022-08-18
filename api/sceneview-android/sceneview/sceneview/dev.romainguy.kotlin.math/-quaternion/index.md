//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Quaternion](index.md)

# Quaternion

[androidJvm]\
data class [Quaternion](index.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Construct Quaternion and set each value. The Quaternion will be normalized during construction Default: Identity

## Constructors

| | |
|---|---|
| [Quaternion](-quaternion.md) | [androidJvm]<br>fun [Quaternion](-quaternion.md)(v: [Float3](../-float3/index.md), w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f) |
| [Quaternion](-quaternion.md) | [androidJvm]<br>fun [Quaternion](-quaternion.md)(v: [Float4](../-float4/index.md)) |
| [Quaternion](-quaternion.md) | [androidJvm]<br>fun [Quaternion](-quaternion.md)(q: [Quaternion](index.md)) |
| [Quaternion](-quaternion.md) | [androidJvm]<br>fun [Quaternion](-quaternion.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [div](div.md) | [androidJvm]<br>inline operator fun [div](div.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [get](get.md) | [androidJvm]<br>operator fun [get](get.md)(index: [QuaternionComponent](../-quaternion-component/index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [get](get.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>operator fun [get](get.md)(index1: [QuaternionComponent](../-quaternion-component/index.md), index2: [QuaternionComponent](../-quaternion-component/index.md), index3: [QuaternionComponent](../-quaternion-component/index.md)): [Float3](../-float3/index.md)<br>operator fun [get](get.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float3](../-float3/index.md)<br>operator fun [get](get.md)(index1: [QuaternionComponent](../-quaternion-component/index.md), index2: [QuaternionComponent](../-quaternion-component/index.md), index3: [QuaternionComponent](../-quaternion-component/index.md), index4: [QuaternionComponent](../-quaternion-component/index.md)): [Quaternion](index.md)<br>operator fun [get](get.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index4: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Quaternion](index.md) |
| [invoke](invoke.md) | [androidJvm]<br>inline operator fun [invoke](invoke.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [minus](minus.md) | [androidJvm]<br>inline operator fun [minus](minus.md)(q: [Quaternion](index.md)): [Quaternion](index.md)<br>inline operator fun [minus](minus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [plus](plus.md) | [androidJvm]<br>inline operator fun [plus](plus.md)(q: [Quaternion](index.md)): [Quaternion](index.md)<br>inline operator fun [plus](plus.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [set](set.md) | [androidJvm]<br>operator fun [set](set.md)(index: [QuaternionComponent](../-quaternion-component/index.md), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [QuaternionComponent](../-quaternion-component/index.md), index2: [QuaternionComponent](../-quaternion-component/index.md), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [QuaternionComponent](../-quaternion-component/index.md), index2: [QuaternionComponent](../-quaternion-component/index.md), index3: [QuaternionComponent](../-quaternion-component/index.md), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [QuaternionComponent](../-quaternion-component/index.md), index2: [QuaternionComponent](../-quaternion-component/index.md), index3: [QuaternionComponent](../-quaternion-component/index.md), index4: [QuaternionComponent](../-quaternion-component/index.md), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index4: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [times](times.md) | [androidJvm]<br>inline operator fun [times](times.md)(v: [Float3](../-float3/index.md)): [Float3](../-float3/index.md)<br>inline operator fun [times](times.md)(q: [Quaternion](index.md)): [Quaternion](index.md)<br>inline operator fun [times](times.md)(v: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [toEulerAngles](to-euler-angles.md) | [androidJvm]<br>fun [toEulerAngles](to-euler-angles.md)(): [Float3](../-float3/index.md) |
| [toFloatArray](to-float-array.md) | [androidJvm]<br>fun [toFloatArray](to-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [toMatrix](to-matrix.md) | [androidJvm]<br>fun [toMatrix](to-matrix.md)(): [Mat4](../-mat4/index.md) |
| [transform](transform.md) | [androidJvm]<br>inline fun [transform](transform.md)(block: ([Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) -&gt; [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Quaternion](index.md) |

## Properties

| Name | Summary |
|---|---|
| [imaginary](imaginary.md) | [androidJvm]<br>var [imaginary](imaginary.md): [Float3](../-float3/index.md) |
| [real](real.md) | [androidJvm]<br>var [real](real.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [w](w.md) | [androidJvm]<br>var [w](w.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f |
| [x](x.md) | [androidJvm]<br>var [x](x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f |
| [xyz](xyz.md) | [androidJvm]<br>var [xyz](xyz.md): [Float3](../-float3/index.md) |
| [xyzw](xyzw.md) | [androidJvm]<br>var [xyzw](xyzw.md): [Float4](../-float4/index.md) |
| [y](y.md) | [androidJvm]<br>var [y](y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f |
| [z](z.md) | [androidJvm]<br>var [z](z.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f |

## Extensions

| Name | Summary |
|---|---|
| [eq](../eq.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[eq](../eq.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[eq](../eq.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [gt](../gt.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[gt](../gt.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[gt](../gt.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [gte](../gte.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[gte](../gte.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[gte](../gte.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [lt](../lt.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[lt](../lt.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[lt](../lt.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [lte](../lte.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[lte](../lte.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[lte](../lte.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [neq](../neq.md) | [androidJvm]<br>infix inline fun [Quaternion](index.md).[neq](../neq.md)(b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Bool4](../-bool4/index.md)<br>infix inline fun [Quaternion](index.md).[neq](../neq.md)(b: [Float4](../-float4/index.md)): [Bool4](../-bool4/index.md) |
| [toOldQuaternion](../../io.github.sceneview.math/to-old-quaternion.md) | [androidJvm]<br>fun [Quaternion](index.md).[toOldQuaternion](../../io.github.sceneview.math/to-old-quaternion.md)(): [Quaternion](../../com.google.ar.sceneform.math/-quaternion/index.md) |
| [toRotation](../../io.github.sceneview.math/to-rotation.md) | [androidJvm]<br>fun [Quaternion](index.md).[toRotation](../../io.github.sceneview.math/to-rotation.md)(order: [RotationsOrder](../-rotations-order/index.md) = RotationsOrder.ZYX): [Float3](../-float3/index.md) |
