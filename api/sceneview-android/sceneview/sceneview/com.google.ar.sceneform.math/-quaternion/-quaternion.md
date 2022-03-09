//[sceneview](../../../index.md)/[com.google.ar.sceneform.math](../index.md)/[Quaternion](index.md)/[Quaternion](-quaternion.md)

# Quaternion

[androidJvm]\
open fun [Quaternion](-quaternion.md)()

Construct Quaternion and set to Identity

[androidJvm]\
open fun [Quaternion](-quaternion.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Construct Quaternion and set each value. The Quaternion will be normalized during construction

[androidJvm]\
open fun [Quaternion](-quaternion.md)(q: [Quaternion](index.md))

Construct Quaternion using values from another Quaternion

[androidJvm]\
open fun [Quaternion](-quaternion.md)(axis: [Vector3](../-vector3/index.md), angle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Construct Quaternion using an axis/angle to define the rotation

## Parameters

androidJvm

| | |
|---|---|
| axis | Sets rotation direction |
| angle | Angle size in degrees |

[androidJvm]\
open fun [Quaternion](-quaternion.md)(eulerAngles: [Vector3](../-vector3/index.md))

Construct Quaternion based on eulerAngles.

## See also

androidJvm

| | |
|---|---|
| [eulerAngles(Vector3 eulerAngles)](euler-angles.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| eulerAngles | - the angle in degrees for each axis. |
