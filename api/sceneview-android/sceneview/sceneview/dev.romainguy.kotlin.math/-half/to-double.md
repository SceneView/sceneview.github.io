//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[toDouble](to-double.md)

# toDouble

[androidJvm]\
fun [toDouble](to-double.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Returns the value of this [Half](index.md) as a `double` after a widening primitive conversion.

The following special cases are handled:

- 
   If the input is [Half.NaN](-companion/-na-n.md), the returned value is [Double.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-na-n.html)
- 
   If the input is [Half.POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) or [Half.NEGATIVE_INFINITY](-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md), the returned value is respectively [Double.POSITIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.html) or [Double.NEGATIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.html)
- 
   If the input is 0 (positive or negative), the returned value is +/-0.0f
- 
   Otherwise, the returned value is a normalized double-precision float value

#### Return

The half-precision float value represented by this object converted to type `double`
