//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Vector3](index.md)

# Vector3

[androidJvm]\
open class [Vector3](index.md)

A Vector with 3 floats.

## Constructors

| | |
|---|---|
| [Vector3](-vector3.md) | [androidJvm]<br>open fun [Vector3](-vector3.md)()<br>Construct a Vector3 and assign zero to all values |
| [Vector3](-vector3.md) | [androidJvm]<br>open fun [Vector3](-vector3.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Construct a Vector3 and assign each value |
| [Vector3](-vector3.md) | [androidJvm]<br>open fun [Vector3](-vector3.md)(v: [Vector3](index.md))<br>Construct a Vector3 and copy the values |

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [androidJvm]<br>open fun [add](add.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md)<br>Adds two Vector3's |
| [angleBetweenVectors](angle-between-vectors.md) | [androidJvm]<br>open fun [angleBetweenVectors](angle-between-vectors.md)(a: [Vector3](index.md), b: [Vector3](index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Returns the shortest angle in degrees between two vectors. |
| [back](back.md) | [androidJvm]<br>open fun [back](back.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (0, 0, 1) |
| [cross](cross.md) | [androidJvm]<br>open fun [cross](cross.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md)<br>Get cross product of two Vector3's |
| [dot](dot.md) | [androidJvm]<br>open fun [dot](dot.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get dot product of two Vector3's |
| [down](down.md) | [androidJvm]<br>open fun [down](down.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (0, -1, 0) |
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if the other object is a Vector3 and each component is equal within a tolerance.<br>[androidJvm]<br>open fun [equals](equals.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares two Vector3's are equal if each component is equal within a tolerance. |
| [forward](forward.md) | [androidJvm]<br>open fun [forward](forward.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (0, 0, -1) |
| [hashCode](hash-code.md) | [androidJvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [left](left.md) | [androidJvm]<br>open fun [left](left.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (-1, 0, 0) |
| [length](length.md) | [androidJvm]<br>open fun [length](length.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [lengthSquared](length-squared.md) | [androidJvm]<br>open fun [lengthSquared](length-squared.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [lerp](lerp.md) | [androidJvm]<br>open fun [lerp](lerp.md)(a: [Vector3](index.md), b: [Vector3](index.md), t: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Vector3](index.md)<br>Linearly interpolates between a and b. |
| [max](max.md) | [androidJvm]<br>open fun [max](max.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md)<br>Get a Vector3 with each value set to the element wise maximum of two Vector3's values |
| [min](min.md) | [androidJvm]<br>open fun [min](min.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md)<br>Get a Vector3 with each value set to the element wise minimum of two Vector3's values |
| [multiply](multiply.md) | [androidJvm]<br>open fun [multiply](multiply.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md) |
| [negated](negated.md) | [androidJvm]<br>open fun [negated](negated.md)(): [Vector3](index.md)<br>Negates a Vector3 |
| [normalized](normalized.md) | [androidJvm]<br>open fun [normalized](normalized.md)(): [Vector3](index.md)<br>Scales the Vector3 to the unit length |
| [one](one.md) | [androidJvm]<br>open fun [one](one.md)(): [Vector3](index.md)<br>Gets a Vector3 with all values set to one |
| [right](right.md) | [androidJvm]<br>open fun [right](right.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (1, 0, 0) |
| [scaled](scaled.md) | [androidJvm]<br>open fun [scaled](scaled.md)(a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Vector3](index.md)<br>Uniformly scales a Vector3 |
| [set](set.md) | [androidJvm]<br>open fun [set](set.md)(v: [Vector3](index.md))<br>Copy the values from another Vector3 to this Vector3<br>[androidJvm]<br>open fun [set](set.md)(vx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), vy: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), vz: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Set each value |
| [subtract](subtract.md) | [androidJvm]<br>open fun [subtract](subtract.md)(lhs: [Vector3](index.md), rhs: [Vector3](index.md)): [Vector3](index.md)<br>Subtract two Vector3 |
| [toString](to-string.md) | [androidJvm]<br>open fun [toString](to-string.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [up](up.md) | [androidJvm]<br>open fun [up](up.md)(): [Vector3](index.md)<br>Gets a Vector3 set to (0, 1, 0) |
| [zero](zero.md) | [androidJvm]<br>open fun [zero](zero.md)(): [Vector3](index.md)<br>Gets a Vector3 with all values set to zero |

## Properties

| Name | Summary |
|---|---|
| [x](x.md) | [androidJvm]<br>open val [x](x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [y](y.md) | [androidJvm]<br>open val [y](y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [z](z.md) | [androidJvm]<br>open val [z](z.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |

## Extensions

| Name | Summary |
|---|---|
| [toFloat3](../../io.github.sceneview.math/to-float3.md) | [androidJvm]<br>fun [Vector3](index.md).[toFloat3](../../io.github.sceneview.math/to-float3.md)(): [Float3](../../dev.romainguy.kotlin.math/-float3/index.md) |
