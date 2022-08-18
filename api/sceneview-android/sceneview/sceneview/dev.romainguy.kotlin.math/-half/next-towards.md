//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[nextTowards](next-towards.md)

# nextTowards

[androidJvm]\
fun [nextTowards](next-towards.md)(to: [Half](index.md)): [Half](index.md)

Returns the [Half](index.md) value nearest to this value in direction from this value towards the value [to](next-towards.md).

Special cases:

- 
   x.nextTowards(y) is NaN if either x or y are NaN
- 
   x.nextTowards(x) == x
