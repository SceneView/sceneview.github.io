//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Quaternion](index.md)/[equals](equals.md)

# equals

[androidJvm]\
open fun [equals](equals.md)(lhs: [Quaternion](index.md), rhs: [Quaternion](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Compare two Quaternions 

Tests for equality by calculating the dot product of lhs and rhs. lhs and -lhs will not be equal according to this function.

[androidJvm]\
open fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Returns true if the other object is a Quaternion and the dot product is 1.0 +/- a tolerance.
