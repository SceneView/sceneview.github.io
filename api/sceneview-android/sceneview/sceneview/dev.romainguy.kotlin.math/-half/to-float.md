//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[toFloat](to-float.md)

# toFloat

[androidJvm]\
fun [toFloat](to-float.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

Returns the value of this [Half](index.md) as a `float` after a widening primitive conversion.

The following special cases are handled:

- 
   If the input is [Half.NaN](-companion/-na-n.md), the returned value is [Float.NaN](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/-na-n.html)
- 
   If the input is [Half.POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) or [Half.NEGATIVE_INFINITY](-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md), the returned value is respectively [Float.POSITIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.html) or [Float.NEGATIVE_INFINITY](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.html)
- 
   If the input is 0 (positive or negative), the returned value is +/-0.0f
- 
   Otherwise, the returned value is a normalized single-precision float value

#### Return

The half-precision float value represented by this object converted to type `float`
