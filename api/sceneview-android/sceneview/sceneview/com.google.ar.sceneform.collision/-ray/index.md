//[sceneview](../../../index.md)/[com.google.ar.sceneform.collision](../index.md)/[Ray](index.md)

# Ray

[androidJvm]\
open class [Ray](index.md)

Mathematical representation of a ray. Used to perform intersection and collision tests.

## Constructors

| | |
|---|---|
| [Ray](-ray.md) | [androidJvm]<br>open fun [Ray](-ray.md)()<br>Create a ray with an origin of (0,0,0) and a direction of Vector3.forward(). |
| [Ray](-ray.md) | [androidJvm]<br>open fun [Ray](-ray.md)(origin: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), direction: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md))<br>Create a ray with a specified origin and direction. |

## Functions

| Name | Summary |
|---|---|
| [getPoint](get-point.md) | [androidJvm]<br>open fun [getPoint](get-point.md)(distance: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Get a point at a distance along the ray. |
| [toString](to-string.md) | [androidJvm]<br>open fun [toString](to-string.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [direction](direction.md) | [androidJvm]<br>private open var [direction](direction.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [origin](origin.md) | [androidJvm]<br>private open var [origin](origin.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
