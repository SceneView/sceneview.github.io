//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Rational](index.md)

# Rational

[androidJvm]\
@[JvmInline](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-inline/index.html)

value class [Rational](index.md)(r: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)&lt;[Rational](index.md)&gt;

## Constructors

| | |
|---|---|
| [Rational](-rational.md) | [androidJvm]<br>fun [Rational](-rational.md)(r: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [androidJvm]<br>open operator override fun [compareTo](compare-to.md)(other: [Rational](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [component1](component1.md) | [androidJvm]<br>fun [component1](component1.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [component2](component2.md) | [androidJvm]<br>fun [component2](component2.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [div](div.md) | [androidJvm]<br>operator fun [div](div.md)(other: [Rational](index.md)): [Rational](index.md) |
| [isFinite](is-finite.md) | [androidJvm]<br>fun [isFinite](is-finite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isInfinite](is-infinite.md) | [androidJvm]<br>fun [isInfinite](is-infinite.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNaN](is-na-n.md) | [androidJvm]<br>fun [isNaN](is-na-n.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isZero](is-zero.md) | [androidJvm]<br>fun [isZero](is-zero.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [minus](minus.md) | [androidJvm]<br>operator fun [minus](minus.md)(other: [Rational](index.md)): [Rational](index.md) |
| [plus](plus.md) | [androidJvm]<br>operator fun [plus](plus.md)(other: [Rational](index.md)): [Rational](index.md) |
| [times](times.md) | [androidJvm]<br>operator fun [times](times.md)(other: [Rational](index.md)): [Rational](index.md) |
| [toDouble](to-double.md) | [androidJvm]<br>fun [toDouble](to-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [toFloat](to-float.md) | [androidJvm]<br>fun [toFloat](to-float.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [toInt](to-int.md) | [androidJvm]<br>fun [toInt](to-int.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toLong](to-long.md) | [androidJvm]<br>fun [toLong](to-long.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [toString](to-string.md) | [androidJvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [unaryMinus](unary-minus.md) | [androidJvm]<br>operator fun [unaryMinus](unary-minus.md)(): [Rational](index.md) |
| [unaryPlus](unary-plus.md) | [androidJvm]<br>operator fun [unaryPlus](unary-plus.md)(): [Rational](index.md) |

## Properties

| Name | Summary |
|---|---|
| [denominator](denominator.md) | [androidJvm]<br>val [denominator](denominator.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [numerator](numerator.md) | [androidJvm]<br>val [numerator](numerator.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [sign](sign.md) | [androidJvm]<br>val [sign](sign.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Extensions

| Name | Summary |
|---|---|
| [toHalf](../to-half.md) | [androidJvm]<br>fun [Rational](index.md).[toHalf](../to-half.md)(): [Half](../-half/index.md)<br>Returns the half-precision float value represented by the specified [Rational](index.md). |
