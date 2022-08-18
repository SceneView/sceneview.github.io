//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[ulp](ulp.md)

# ulp

[androidJvm]\
val [ulp](ulp.md): [Half](index.md)

Returns the ulp of this value. An ulp is a positive distance between this value and the next nearest [Half](index.md) value larger in magnitude.

Special Cases:

- 
   NaN.ulp is [NaN](-companion/-na-n.md)
- 
   x.ulp is [POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) when x is [POSITIVE_INFINITY](-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md) or [NEGATIVE_INFINITY](-companion/-n-e-g-a-t-i-v-e_-i-n-f-i-n-i-t-y.md)
- 
   0.0.ulp is [MIN_VALUE](-companion/-m-i-n_-v-a-l-u-e.md)
