//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half4](index.md)

# Half4

[androidJvm]\
data class [Half4](index.md)(var x: [Half](../-half/index.md) = Half.POSITIVE_ZERO, var y: [Half](../-half/index.md) = Half.POSITIVE_ZERO, var z: [Half](../-half/index.md) = Half.POSITIVE_ZERO, var w: [Half](../-half/index.md) = Half.POSITIVE_ZERO)

## Constructors

| | |
|---|---|
| [Half4](-half4.md) | [androidJvm]<br>fun [Half4](-half4.md)(v: [Half](../-half/index.md)) |
| [Half4](-half4.md) | [androidJvm]<br>fun [Half4](-half4.md)(v: [Half2](../-half2/index.md), z: [Half](../-half/index.md) = Half.POSITIVE_ZERO, w: [Half](../-half/index.md) = Half.POSITIVE_ZERO) |
| [Half4](-half4.md) | [androidJvm]<br>fun [Half4](-half4.md)(v: [Half3](../-half3/index.md), w: [Half](../-half/index.md) = Half.POSITIVE_ZERO) |
| [Half4](-half4.md) | [androidJvm]<br>fun [Half4](-half4.md)(v: [Half4](index.md)) |
| [Half4](-half4.md) | [androidJvm]<br>fun [Half4](-half4.md)(x: [Half](../-half/index.md) = Half.POSITIVE_ZERO, y: [Half](../-half/index.md) = Half.POSITIVE_ZERO, z: [Half](../-half/index.md) = Half.POSITIVE_ZERO, w: [Half](../-half/index.md) = Half.POSITIVE_ZERO) |

## Functions

| Name | Summary |
|---|---|
| [dec](dec.md) | [androidJvm]<br>operator fun [dec](dec.md)(): [Half4](index.md) |
| [div](div.md) | [androidJvm]<br>inline operator fun [div](div.md)(v: [Half](../-half/index.md)): [Half4](index.md)<br>inline operator fun [div](div.md)(v: [Half2](../-half2/index.md)): [Half4](index.md)<br>inline operator fun [div](div.md)(v: [Half3](../-half3/index.md)): [Half4](index.md)<br>inline operator fun [div](div.md)(v: [Half4](index.md)): [Half4](index.md) |
| [get](get.md) | [androidJvm]<br>operator fun [get](get.md)(index: [VectorComponent](../-vector-component/index.md)): [Half](../-half/index.md)<br>operator fun [get](get.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Half](../-half/index.md)<br>operator fun [get](get.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md)): [Half2](../-half2/index.md)<br>operator fun [get](get.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Half2](../-half2/index.md)<br>operator fun [get](get.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md), index3: [VectorComponent](../-vector-component/index.md)): [Half3](../-half3/index.md)<br>operator fun [get](get.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Half3](../-half3/index.md)<br>operator fun [get](get.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md), index3: [VectorComponent](../-vector-component/index.md), index4: [VectorComponent](../-vector-component/index.md)): [Half4](index.md)<br>operator fun [get](get.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index4: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Half4](index.md) |
| [inc](inc.md) | [androidJvm]<br>operator fun [inc](inc.md)(): [Half4](index.md) |
| [invoke](invoke.md) | [androidJvm]<br>inline operator fun [invoke](invoke.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Half](../-half/index.md) |
| [minus](minus.md) | [androidJvm]<br>inline operator fun [minus](minus.md)(v: [Half](../-half/index.md)): [Half4](index.md)<br>inline operator fun [minus](minus.md)(v: [Half2](../-half2/index.md)): [Half4](index.md)<br>inline operator fun [minus](minus.md)(v: [Half3](../-half3/index.md)): [Half4](index.md)<br>inline operator fun [minus](minus.md)(v: [Half4](index.md)): [Half4](index.md) |
| [plus](plus.md) | [androidJvm]<br>inline operator fun [plus](plus.md)(v: [Half](../-half/index.md)): [Half4](index.md)<br>inline operator fun [plus](plus.md)(v: [Half2](../-half2/index.md)): [Half4](index.md)<br>inline operator fun [plus](plus.md)(v: [Half3](../-half3/index.md)): [Half4](index.md)<br>inline operator fun [plus](plus.md)(v: [Half4](index.md)): [Half4](index.md) |
| [set](set.md) | [androidJvm]<br>operator fun [set](set.md)(index: [VectorComponent](../-vector-component/index.md), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md), index3: [VectorComponent](../-vector-component/index.md), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [VectorComponent](../-vector-component/index.md), index2: [VectorComponent](../-vector-component/index.md), index3: [VectorComponent](../-vector-component/index.md), index4: [VectorComponent](../-vector-component/index.md), v: [Half](../-half/index.md))<br>operator fun [set](set.md)(index1: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index2: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index3: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), index4: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), v: [Half](../-half/index.md)) |
| [times](times.md) | [androidJvm]<br>inline operator fun [times](times.md)(v: [Half](../-half/index.md)): [Half4](index.md)<br>inline operator fun [times](times.md)(v: [Half2](../-half2/index.md)): [Half4](index.md)<br>inline operator fun [times](times.md)(v: [Half3](../-half3/index.md)): [Half4](index.md)<br>inline operator fun [times](times.md)(v: [Half4](index.md)): [Half4](index.md) |
| [toFloatArray](to-float-array.md) | [androidJvm]<br>fun [toFloatArray](to-float-array.md)(): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html) |
| [transform](transform.md) | [androidJvm]<br>inline fun [transform](transform.md)(block: ([Half](../-half/index.md)) -&gt; [Half](../-half/index.md)): [Half4](index.md) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Half4](index.md) |

## Properties

| Name | Summary |
|---|---|
| [a](a.md) | [androidJvm]<br>var [a](a.md): [Half](../-half/index.md) |
| [b](b.md) | [androidJvm]<br>var [b](b.md): [Half](../-half/index.md) |
| [g](g.md) | [androidJvm]<br>var [g](g.md): [Half](../-half/index.md) |
| [p](p.md) | [androidJvm]<br>var [p](p.md): [Half](../-half/index.md) |
| [q](q.md) | [androidJvm]<br>var [q](q.md): [Half](../-half/index.md) |
| [r](r.md) | [androidJvm]<br>var [r](r.md): [Half](../-half/index.md) |
| [rg](rg.md) | [androidJvm]<br>var [rg](rg.md): [Half2](../-half2/index.md) |
| [rgb](rgb.md) | [androidJvm]<br>var [rgb](rgb.md): [Half3](../-half3/index.md) |
| [rgba](rgba.md) | [androidJvm]<br>var [rgba](rgba.md): [Half4](index.md) |
| [s](s.md) | [androidJvm]<br>var [s](s.md): [Half](../-half/index.md) |
| [st](st.md) | [androidJvm]<br>var [st](st.md): [Half2](../-half2/index.md) |
| [stp](stp.md) | [androidJvm]<br>var [stp](stp.md): [Half3](../-half3/index.md) |
| [stpq](stpq.md) | [androidJvm]<br>var [stpq](stpq.md): [Half4](index.md) |
| [t](t.md) | [androidJvm]<br>var [t](t.md): [Half](../-half/index.md) |
| [w](w.md) | [androidJvm]<br>var [w](w.md): [Half](../-half/index.md) |
| [x](x.md) | [androidJvm]<br>var [x](x.md): [Half](../-half/index.md) |
| [xy](xy.md) | [androidJvm]<br>var [xy](xy.md): [Half2](../-half2/index.md) |
| [xyz](xyz.md) | [androidJvm]<br>var [xyz](xyz.md): [Half3](../-half3/index.md) |
| [xyzw](xyzw.md) | [androidJvm]<br>var [xyzw](xyzw.md): [Half4](index.md) |
| [y](y.md) | [androidJvm]<br>var [y](y.md): [Half](../-half/index.md) |
| [z](z.md) | [androidJvm]<br>var [z](z.md): [Half](../-half/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [eq](../eq.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[eq](../eq.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[eq](../eq.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
| [gt](../gt.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[gt](../gt.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[gt](../gt.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
| [gte](../gte.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[gte](../gte.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[gte](../gte.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
| [lt](../lt.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[lt](../lt.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[lt](../lt.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
| [lte](../lte.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[lte](../lte.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[lte](../lte.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
| [neq](../neq.md) | [androidJvm]<br>infix inline fun [Half4](index.md).[neq](../neq.md)(b: [Half](../-half/index.md)): [Bool4](../-bool4/index.md)<br>infix inline fun [Half4](index.md).[neq](../neq.md)(b: [Half4](index.md)): [Bool4](../-bool4/index.md) |
