//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Matrix](index.md)

# Matrix

[androidJvm]\
open class [Matrix](index.md)

4x4 Matrix representing translation, scale, and rotation. Column major, right handed [0, 4, 8, 12] [1, 5, 9, 13] [2, 6, 10, 14] [3, 7, 11, 15]

## Constructors

| | |
|---|---|
| [Matrix](-matrix.md) | [androidJvm]<br>open fun [Matrix](-matrix.md)() |
| [Matrix](-matrix.md) | [androidJvm]<br>open fun [Matrix](-matrix.md)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;) |

## Functions

| Name | Summary |
|---|---|
| [decomposeRotation](decompose-rotation.md) | [androidJvm]<br>open fun [decomposeRotation](decompose-rotation.md)(decomposedScale: [Vector3](../-vector3/index.md), destMatrix: [Matrix](index.md))<br>open fun [decomposeRotation](decompose-rotation.md)(decomposedScale: [Vector3](../-vector3/index.md), destRotation: [Quaternion](../-quaternion/index.md)) |
| [decomposeScale](decompose-scale.md) | [androidJvm]<br>open fun [decomposeScale](decompose-scale.md)(destScale: [Vector3](../-vector3/index.md)) |
| [decomposeTranslation](decompose-translation.md) | [androidJvm]<br>open fun [decomposeTranslation](decompose-translation.md)(destTranslation: [Vector3](../-vector3/index.md)) |
| [equals](equals.md) | [androidJvm]<br>open fun [equals](equals.md)(lhs: [Matrix](index.md), rhs: [Matrix](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares Matrix values |
| [extractQuaternion](extract-quaternion.md) | [androidJvm]<br>open fun [extractQuaternion](extract-quaternion.md)(destQuaternion: [Quaternion](../-quaternion/index.md)) |
| [invert](invert.md) | [androidJvm]<br>open fun [invert](invert.md)(matrix: [Matrix](index.md), dest: [Matrix](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [makeRotation](make-rotation.md) | [androidJvm]<br>open fun [makeRotation](make-rotation.md)(rotation: [Quaternion](../-quaternion/index.md)) |
| [makeScale](make-scale.md) | [androidJvm]<br>open fun [makeScale](make-scale.md)(scale: [Vector3](../-vector3/index.md))<br>open fun [makeScale](make-scale.md)(scale: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [makeTranslation](make-translation.md) | [androidJvm]<br>open fun [makeTranslation](make-translation.md)(translation: [Vector3](../-vector3/index.md)) |
| [makeTrs](make-trs.md) | [androidJvm]<br>open fun [makeTrs](make-trs.md)(translation: [Vector3](../-vector3/index.md), rotation: [Quaternion](../-quaternion/index.md), scale: [Vector3](../-vector3/index.md)) |
| [multiply](multiply.md) | [androidJvm]<br>open fun [multiply](multiply.md)(lhs: [Matrix](index.md), rhs: [Matrix](index.md), dest: [Matrix](index.md)) |
| [set](set.md) | [androidJvm]<br>open fun [set](set.md)(m: [Matrix](index.md))<br>open fun [set](set.md)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;) |
| [setTranslation](set-translation.md) | [androidJvm]<br>open fun [setTranslation](set-translation.md)(translation: [Vector3](../-vector3/index.md)) |
| [transformDirection](transform-direction.md) | [androidJvm]<br>open fun [transformDirection](transform-direction.md)(vector: [Vector3](../-vector3/index.md)): [Vector3](../-vector3/index.md)<br>Transforms a direction by ignoring any translation. |
| [transformPoint](transform-point.md) | [androidJvm]<br>open fun [transformPoint](transform-point.md)(vector: [Vector3](../-vector3/index.md)): [Vector3](../-vector3/index.md) |

## Properties

| Name | Summary |
|---|---|
| [data](data.md) | [androidJvm]<br>open var [data](data.md): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt; |
| [IDENTITY_DATA](-i-d-e-n-t-i-t-y_-d-a-t-a.md) | [androidJvm]<br>val [IDENTITY_DATA](-i-d-e-n-t-i-t-y_-d-a-t-a.md): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt; |
