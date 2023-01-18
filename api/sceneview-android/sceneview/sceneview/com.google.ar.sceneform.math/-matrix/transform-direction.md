//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Matrix](index.md)/[transformDirection](transform-direction.md)

# transformDirection

[androidJvm]\
open fun [transformDirection](transform-direction.md)(vector: [Vector3](../-vector3/index.md)): [Vector3](../-vector3/index.md)

Transforms a direction by ignoring any translation. 

If the matrix is uniformly (positively) scaled, then the resulting direction will be correct but scaled by the same factor. If a unit direction is required then the result should be normalized. 

If the scale is non-uniform or negative then the result vector will be distorted. In this case the matrix used should be the inverse transpose of the incoming matrix.
