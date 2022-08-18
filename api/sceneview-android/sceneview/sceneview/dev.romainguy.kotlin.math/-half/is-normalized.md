//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[isNormalized](is-normalized.md)

# isNormalized

[androidJvm]\
fun [isNormalized](is-normalized.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Returns true if this half-precision float value is normalized (does not have a subnormal representation). If this value is [Half.POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md), [Half.NEGATIVE_INFINITY](-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md), [Half.POSITIVE_ZERO](-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md), [Half.NEGATIVE_ZERO](-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md), NaN or any subnormal number, this method returns false.

#### Return

True if the value is normalized, false otherwise
