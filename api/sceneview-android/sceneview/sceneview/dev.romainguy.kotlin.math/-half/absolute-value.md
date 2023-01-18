//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[absoluteValue](absolute-value.md)

# absoluteValue

[androidJvm]\
val [absoluteValue](absolute-value.md): [Half](index.md)

Returns the absolute value of this half-precision float. Special values are handled in the following ways:

- 
   If the specified half-precision float is NaN, the result is NaN
- 
   If the specified half-precision float is zero (negative or positive), the result is positive zero (see [POSITIVE_ZERO](-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md))
- 
   If the specified half-precision float is infinity (negative or positive), the result is positive infinity (see [POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md))

#### Return

The absolute value of the specified half-precision float
