//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[toHalf](to-half.md)

# toHalf

[androidJvm]\
fun [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html).[toHalf](to-half.md)(): [Half](-half/index.md)

Converts this double-precision float value into a half-precision float value. The following special cases are handled:

- 
   If the input is NaN (see [Double.isNaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/index.html)), the returned value is [Half.NaN](-half/-companion/-na-n.md)
- 
   If the input is [Double.POSITIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.html) or [Double.NEGATIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.html), the returned value is respectively [Half.POSITIVE_INFINITY](-half/-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) or [Half.NEGATIVE_INFINITY](-half/-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md)
- 
   If the input is 0 (positive or negative), the returned value is [Half.POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md) or [Half.NEGATIVE_ZERO](-half/-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md)
- 
   If the input is less than [Half.MIN_VALUE](-half/-companion/-m-i-n_-v-a-l-u-e.md), the returned value is flushed to [Half.POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md) or [Half.NEGATIVE_ZERO](-half/-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md)
- 
   If the input is less than [Half.MIN_NORMAL](-half/-companion/-m-i-n_-n-o-r-m-a-l.md), the returned value is a denormal half-precision float
- 
   Otherwise, the returned value is rounded to the nearest representable half-precision float value

#### Return

A half-precision float value

[androidJvm]\
fun [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html).[toHalf](to-half.md)(): [Half](-half/index.md)

Converts this single-precision float value into a half-precision float value. The following special cases are handled:

- 
   If the input is NaN (see [Float.isNaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/index.html)), the returned value is [Half.NaN](-half/-companion/-na-n.md)
- 
   If the input is [Float.POSITIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.html) or [Float.NEGATIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.html), the returned value is respectively [Half.POSITIVE_INFINITY](-half/-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) or [Half.NEGATIVE_INFINITY](-half/-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md)
- 
   If the input is 0 (positive or negative), the returned value is [Half.POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md) or [Half.NEGATIVE_ZERO](-half/-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md)
- 
   If the input is less than [Half.MIN_VALUE](-half/-companion/-m-i-n_-v-a-l-u-e.md), the returned value is flushed to [Half.POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md) or [Half.NEGATIVE_ZERO](-half/-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md)
- 
   If the input is less than [Half.MIN_NORMAL](-half/-companion/-m-i-n_-n-o-r-m-a-l.md), the returned value is a denormal half-precision float
- 
   Otherwise, the returned value is rounded to the nearest representable half-precision float value

#### Return

A half-precision float value

[androidJvm]\
fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[toHalf](to-half.md)(): [Half](-half/index.md)

Returns the half-precision float value represented by the specified string. The string is converted to a half-precision float value as if by the [String.toFloat()](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) method.</p>

Calling this function is equivalent to calling:

Half(value.toFloat())

## See also

androidJvm

| | |
|---|---|
| [String.toFloat](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/index.html) |  |

## Throws

| | |
|---|---|
| [kotlin.NumberFormatException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number-format-exception/index.html) | if the string does not contain a parsable number |

[androidJvm]\
fun [Rational](-rational/index.md).[toHalf](to-half.md)(): [Half](-half/index.md)

Returns the half-precision float value represented by the specified [Rational](-rational/index.md).
