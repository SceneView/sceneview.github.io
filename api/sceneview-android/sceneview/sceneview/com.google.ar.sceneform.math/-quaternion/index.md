//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Quaternion](index.md)

# Quaternion

[androidJvm]\
open class [Quaternion](index.md)

A Sceneform quaternion class for floats. 

Quaternion operations are Hamiltonian using the right-hand-rule convention.

## Constructors

| | |
|---|---|
| [Quaternion](-quaternion.md) | [androidJvm]<br>open fun [Quaternion](-quaternion.md)()<br>Construct Quaternion and set to Identity |
| [Quaternion](-quaternion.md) | [androidJvm]<br>open fun [Quaternion](-quaternion.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Construct Quaternion and set each value. |
| [Quaternion](-quaternion.md) | [androidJvm]<br>open fun [Quaternion](-quaternion.md)(q: [Quaternion](index.md))<br>Construct Quaternion using values from another Quaternion |
| [Quaternion](-quaternion.md) | [androidJvm]<br>open fun [Quaternion](-quaternion.md)(axis: [Vector3](../-vector3/index.md), angle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Construct Quaternion using an axis/angle to define the rotation |
| [Quaternion](-quaternion.md) | [androidJvm]<br>open fun [Quaternion](-quaternion.md)(eulerAngles: [Vector3](../-vector3/index.md))<br>Construct Quaternion based on eulerAngles. |

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [androidJvm]<br>open fun [add](add.md)(lhs: [Quaternion](index.md), rhs: [Quaternion](index.md)): [Quaternion](index.md)<br>Adds two Quaternion's without normalizing |
| [axisAngle](axis-angle.md) | [androidJvm]<br>open fun [axisAngle](axis-angle.md)(axis: [Vector3](../-vector3/index.md), degrees: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md)<br>Get a new Quaternion using an axis/angle to define the rotation |
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if the other object is a Quaternion and the dot product is 1.0 +/- a tolerance.<br>[androidJvm]<br>open fun [equals](equals.md)(lhs: [Quaternion](index.md), rhs: [Quaternion](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compare two Quaternions Tests for equality by calculating the dot product of lhs and rhs. |
| [eulerAngles](euler-angles.md) | [androidJvm]<br>open fun [eulerAngles](euler-angles.md)(eulerAngles: [Vector3](../-vector3/index.md)): [Quaternion](index.md)<br>Get a new Quaternion using eulerAngles to define the rotation. |
| [getEulerAngles](get-euler-angles.md) | [androidJvm]<br>open fun [getEulerAngles](get-euler-angles.md)(): [Vector3](../-vector3/index.md) |
| [hashCode](hash-code.md) | [androidJvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [identity](identity.md) | [androidJvm]<br>open fun [identity](identity.md)(): [Quaternion](index.md)<br>Get a Quaternion set to identity |
| [inverseRotateVector](inverse-rotate-vector.md) | [androidJvm]<br>open fun [inverseRotateVector](inverse-rotate-vector.md)(q: [Quaternion](index.md), src: [Vector3](../-vector3/index.md)): [Vector3](../-vector3/index.md) |
| [inverted](inverted.md) | [androidJvm]<br>open fun [inverted](inverted.md)(): [Quaternion](index.md)<br>Get a Quaternion with the opposite rotation |
| [lookRotation](look-rotation.md) | [androidJvm]<br>open fun [lookRotation](look-rotation.md)(forwardInWorld: [Vector3](../-vector3/index.md), desiredUpInWorld: [Vector3](../-vector3/index.md)): [Quaternion](index.md)<br>Get a new Quaternion representing a rotation towards a specified forward direction. |
| [multiply](multiply.md) | [androidJvm]<br>open fun [multiply](multiply.md)(lhs: [Quaternion](index.md), rhs: [Quaternion](index.md)): [Quaternion](index.md)<br>Create a Quaternion by combining two Quaternions multiply(lhs, rhs) is equivalent to performing the rhs rotation then lhs rotation Ordering is important for this operation. |
| [negated](negated.md) | [androidJvm]<br>open fun [negated](negated.md)(): [Quaternion](index.md)<br>Flips the sign of the Quaternion, but represents the same rotation. |
| [normalize](normalize.md) | [androidJvm]<br>open fun [normalize](normalize.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Rescales the quaternion to the unit length. |
| [normalized](normalized.md) | [androidJvm]<br>open fun [normalized](normalized.md)(): [Quaternion](index.md)<br>Get a Quaternion with a matching rotation but scaled to unit length. |
| [rotateVector](rotate-vector.md) | [androidJvm]<br>open fun [rotateVector](rotate-vector.md)(q: [Quaternion](index.md), src: [Vector3](../-vector3/index.md)): [Vector3](../-vector3/index.md)<br>Rotates a Vector3 by a Quaternion |
| [rotationBetweenVectors](rotation-between-vectors.md) | [androidJvm]<br>open fun [rotationBetweenVectors](rotation-between-vectors.md)(start: [Vector3](../-vector3/index.md), end: [Vector3](../-vector3/index.md)): [Quaternion](index.md)<br>Get a new Quaternion representing the rotation from one vector to another. |
| [set](set.md) | [androidJvm]<br>open fun [set](set.md)(q: [Quaternion](index.md))<br>Copy values from another Quaternion into this one<br>[androidJvm]<br>open fun [set](set.md)(axis: [Vector3](../-vector3/index.md), angle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Update this Quaternion using an axis/angle to define the rotation<br>[androidJvm]<br>open fun [set](set.md)(qx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), qy: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), qz: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), qw: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Set each value and normalize the Quaternion |
| [setIdentity](set-identity.md) | [androidJvm]<br>open fun [setIdentity](set-identity.md)()<br>Set the Quaternion to identity |
| [slerp](slerp.md) | [androidJvm]<br>open fun [slerp](slerp.md)(start: [Quaternion](index.md), end: [Quaternion](index.md), t: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Quaternion](index.md) |
| [toString](to-string.md) | [androidJvm]<br>open fun [toString](to-string.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [w](w.md) | [androidJvm]<br>open var [w](w.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [x](x.md) | [androidJvm]<br>open var [x](x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [y](y.md) | [androidJvm]<br>open var [y](y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [z](z.md) | [androidJvm]<br>open var [z](z.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |

## Extensions

| Name | Summary |
|---|---|
| [toNewQuaternion](../../io.github.sceneview.math/to-new-quaternion.md) | [androidJvm]<br>fun [Quaternion](index.md).[toNewQuaternion](../../io.github.sceneview.math/to-new-quaternion.md)(): [Quaternion](../../dev.romainguy.kotlin.math/-quaternion/index.md) |
