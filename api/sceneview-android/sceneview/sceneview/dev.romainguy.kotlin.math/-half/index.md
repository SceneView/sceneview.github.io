//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)

# Half

[androidJvm]\
@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)

value class [Half](index.md)(v: [UShort](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-short/index.html)) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)&lt;[Half](index.md)&gt; 

The [Half](index.md) class is a wrapper and a utility class to manipulate half-precision 16-bit [IEEE 754](https://en.wikipedia.org/wiki/Half-precision_floating-point_format) floating point data types (also called fp16 or binary16). A half-precision float can be created from or converted to single-precision floats, and is stored in a short data type.

The IEEE 754 standard specifies an fp16 as having the following format:

- 
   Sign bit: 1 bit
- 
   Exponent width: 5 bits
- 
   Significand: 10 bits

The format is laid out as follows:

1   11111   1111111111\
^   --^--   -----^----\
sign  |          |_______ significand\
      |\
      -- exponent

Half-precision floating points can be useful to save memory and/or bandwidth at the expense of range and precision when compared to single-precision floating points (fp32).

To help you decide whether fp16 is the right storage type for you need, please refer to the table below that shows the available precision throughout the range of possible values. The *precision* column indicates the step size between two consecutive numbers in a specific part of the range.

| Range start | Precision |
|---|---|
| 0 | 1 ⁄ 16,777,216 |
| 1 ⁄ 16,384 | 1 ⁄ 16,777,216 |
| 1 ⁄ 8,192 | 1 ⁄ 8,388,608 |
| 1 ⁄ 4,096 | 1 ⁄ 4,194,304 |
| 1 ⁄ 2,048 | 1 ⁄ 2,097,152 |
| 1 ⁄ 1,024 | 1 ⁄ 1,048,576 |
| 1 ⁄ 512 | 1 ⁄ 524,288 |
| 1 ⁄ 256 | 1 ⁄ 262,144 |
| 1 ⁄ 128 | 1 ⁄ 131,072 |
| 1 ⁄ 64 | 1 ⁄ 65,536 |
| 1 ⁄ 32 | 1 ⁄ 32,768 |
| 1 ⁄ 16 | 1 ⁄ 16,384 |
| 1 ⁄ 8 | 1 ⁄ 8,192 |
| 1 ⁄ 4 | 1 ⁄ 4,096 |
| 1 ⁄ 2 | 1 ⁄ 2,048 |
| 1 | 1 ⁄ 1,024 |
| 2 | 1 ⁄ 512 |
| 4 | 1 ⁄ 256 |
| 8 | 1 ⁄ 128 |
| 16 | 1 ⁄ 64 |
| 32 | 1 ⁄ 32 |
| 64 | 1 ⁄ 16 |
| 128 | 1 ⁄ 8 |
| 256 | 1 ⁄ 4 |
| 512 | 1 ⁄ 2 |
| 1,024 | 1 |
| 2,048 | 2 |
| 4,096 | 4 |
| 8,192 | 8 |
| 16,384 | 16 |
| 32,768 | 32 |

This table shows that numbers higher than 1024 lose all fractional precision.

## Constructors

| | |
|---|---|
| [Half](-half.md) | [androidJvm]<br>fun [Half](-half.md)(v: [UShort](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-short/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [androidJvm]<br>open operator override fun [compareTo](compare-to.md)(other: [Half](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [dec](dec.md) | [androidJvm]<br>operator fun [dec](dec.md)(): [Half](index.md) |
| [div](div.md) | [androidJvm]<br>operator fun [div](div.md)(other: [Half](index.md)): [Half](index.md) |
| [inc](inc.md) | [androidJvm]<br>operator fun [inc](inc.md)(): [Half](index.md) |
| [isFinite](is-finite.md) | [androidJvm]<br>fun [isFinite](is-finite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this half-precision float value does not represent infinity nor NaN, false otherwise. |
| [isInfinite](is-infinite.md) | [androidJvm]<br>fun [isInfinite](is-infinite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this half-precision float value represents infinity, false otherwise. |
| [isNaN](is-na-n.md) | [androidJvm]<br>fun [isNaN](is-na-n.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this half-precision float value represents a Not-a-Number, false otherwise. |
| [isNormalized](is-normalized.md) | [androidJvm]<br>fun [isNormalized](is-normalized.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this half-precision float value is normalized (does not have a subnormal representation). If this value is [Half.POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md), [Half.NEGATIVE_INFINITY](-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md), [Half.POSITIVE_ZERO](-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md), [Half.NEGATIVE_ZERO](-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md), NaN or any subnormal number, this method returns false. |
| [isZero](is-zero.md) | [androidJvm]<br>fun [isZero](is-zero.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this half-precision float value represents zero, false otherwise. |
| [minus](minus.md) | [androidJvm]<br>operator fun [minus](minus.md)(other: [Half](index.md)): [Half](index.md) |
| [nextDown](next-down.md) | [androidJvm]<br>fun [nextDown](next-down.md)(): [Half](index.md)<br>Returns the [Half](index.md) value nearest to this value in direction of negative infinity. |
| [nextTowards](next-towards.md) | [androidJvm]<br>fun [nextTowards](next-towards.md)(to: [Half](index.md)): [Half](index.md)<br>Returns the [Half](index.md) value nearest to this value in direction from this value towards the value [to](next-towards.md). |
| [nextUp](next-up.md) | [androidJvm]<br>fun [nextUp](next-up.md)(): [Half](index.md)<br>Returns the [Half](index.md) value nearest to this value in direction of positive infinity. |
| [plus](plus.md) | [androidJvm]<br>operator fun [plus](plus.md)(other: [Half](index.md)): [Half](index.md) |
| [roundToInt](round-to-int.md) | [androidJvm]<br>fun [roundToInt](round-to-int.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Rounds this [Half](index.md) value to the nearest integer and converts the result to [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html). Ties are rounded towards positive infinity. |
| [roundToLong](round-to-long.md) | [androidJvm]<br>fun [roundToLong](round-to-long.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Rounds this [Half](index.md) value to the nearest integer and converts the result to [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html). Ties are rounded towards positive infinity. |
| [times](times.md) | [androidJvm]<br>operator fun [times](times.md)(other: [Half](index.md)): [Half](index.md) |
| [toBits](to-bits.md) | [androidJvm]<br>fun [toBits](to-bits.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns a bit representation of this half-precision floating point value as [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) according to the IEEE 754 floating-point half-precision bit layout. |
| [toByte](to-byte.md) | [androidJvm]<br>fun [toByte](to-byte.md)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>Returns the value of this [Half](index.md) as a byte after a narrowing primitive conversion. |
| [toDouble](to-double.md) | [androidJvm]<br>fun [toDouble](to-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Returns the value of this [Half](index.md) as a double after a widening primitive conversion. |
| [toFloat](to-float.md) | [androidJvm]<br>fun [toFloat](to-float.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Returns the value of this [Half](index.md) as a float after a widening primitive conversion. |
| [toHexString](to-hex-string.md) | [androidJvm]<br>fun [toHexString](to-hex-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns a hexadecimal string representation of the specified half-precision float value. If the value is a NaN, the result is "NaN", otherwise the result follows this format: |
| [toInt](to-int.md) | [androidJvm]<br>fun [toInt](to-int.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the value of this [Half](index.md) as a int after a narrowing primitive conversion. |
| [toLong](to-long.md) | [androidJvm]<br>fun [toLong](to-long.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Returns the value of this [Half](index.md) as a long after a narrowing primitive conversion. |
| [toShort](to-short.md) | [androidJvm]<br>fun [toShort](to-short.md)(): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)<br>Returns the value of this [Half](index.md) as a short after a narrowing primitive conversion. |
| [toString](to-string.md) | [androidJvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Half](index.md) |
| [unaryPlus](unary-plus.md) | [androidJvm]<br>operator fun [unaryPlus](unary-plus.md)(): [Half](index.md) |
| [withSign](with-sign.md) | [androidJvm]<br>fun [withSign](with-sign.md)(sign: [Half](index.md)): [Half](index.md)<br>Returns this value with the sign bit same as of the [sign](with-sign.md) value. If [sign](with-sign.md) is NaN the sign of the result is undefined. |

## Properties

| Name | Summary |
|---|---|
| [absoluteValue](absolute-value.md) | [androidJvm]<br>val [absoluteValue](absolute-value.md): [Half](index.md)<br>Returns the absolute value of this half-precision float. Special values are handled in the following ways: |
| [exponent](exponent.md) | [androidJvm]<br>val [exponent](exponent.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the unbiased exponent used in the representation of this half-precision float value. if the value is NaN or infinite, this method returns [MAX_EXPONENT](-companion/-m-a-x_-e-x-p-o-n-e-n-t.md) + 1. If the argument is 0 or a subnormal representation, this method returns [MIN_EXPONENT](-companion/-m-i-n_-e-x-p-o-n-e-n-t.md) - 1. |
| [sign](sign.md) | [androidJvm]<br>val [sign](sign.md): [Half](index.md)<br>Returns the sign of this half-precision float value: |
| [significand](significand.md) | [androidJvm]<br>val [significand](significand.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the significand, or mantissa, used in the representation of this half-precision float value. |
| [ulp](ulp.md) | [androidJvm]<br>val [ulp](ulp.md): [Half](index.md)<br>Returns the ulp of this value. An ulp is a positive distance between this value and the next nearest [Half](index.md) value larger in magnitude. |

## Extensions

| Name | Summary |
|---|---|
| [div](../div.md) | [androidJvm]<br>inline operator fun [Half](index.md).[div](../div.md)(v: [Half3](../-half3/index.md)): [Half3](../-half3/index.md)<br>inline operator fun [Half](index.md).[div](../div.md)(v: [Half4](../-half4/index.md)): [Half4](../-half4/index.md) |
| [minus](../minus.md) | [androidJvm]<br>inline operator fun [Half](index.md).[minus](../minus.md)(v: [Half3](../-half3/index.md)): [Half3](../-half3/index.md)<br>inline operator fun [Half](index.md).[minus](../minus.md)(v: [Half4](../-half4/index.md)): [Half4](../-half4/index.md) |
| [plus](../plus.md) | [androidJvm]<br>inline operator fun [Half](index.md).[plus](../plus.md)(v: [Half3](../-half3/index.md)): [Half3](../-half3/index.md)<br>inline operator fun [Half](index.md).[plus](../plus.md)(v: [Half4](../-half4/index.md)): [Half4](../-half4/index.md) |
| [times](../times.md) | [androidJvm]<br>inline operator fun [Half](index.md).[times](../times.md)(v: [Half3](../-half3/index.md)): [Half3](../-half3/index.md)<br>inline operator fun [Half](index.md).[times](../times.md)(v: [Half4](../-half4/index.md)): [Half4](../-half4/index.md) |
