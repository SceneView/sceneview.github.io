//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[smoothRotationThreshold](smooth-rotation-threshold.md)

# smoothRotationThreshold

[androidJvm]\
var [smoothRotationThreshold](smooth-rotation-threshold.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

##  The smooth rotation minimum change limit

This is used to avoid very near rotations smooth modifications. It prevents the rotation to appear too quick if the ranges are too close and uses linearly interpolation for upper dot products.

Expressed in quaternion dot product This value is used by [smooth](smooth.md)
