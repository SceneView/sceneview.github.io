//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[PickHitResult](index.md)

# PickHitResult

[androidJvm]\
open class [PickHitResult](index.md) : [RayHit](../../com.google.ar.sceneform.collision/-ray-hit/index.md)

Stores the results of calls to Scene.hitTest and Scene.hitTestAll. Contains a node that was hit by the hit test, and associated information.

## Functions

| Name | Summary |
|---|---|
| [getDistance](index.md#1496805960%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getDistance](index.md#1496805960%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the distance along the ray to the impact point on the surface of the collision shape. |
| [getPoint](index.md#239169357%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getPoint](index.md#239169357%2FFunctions%2F-1571379623)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Get the position in world-space where the ray hit the collision shape. |
| [reset](reset.md) | [androidJvm]<br>open fun [reset](reset.md)() |
| [set](../../com.google.ar.sceneform.collision/-ray-hit/set.md) | [androidJvm]<br>open fun [set](../../com.google.ar.sceneform.collision/-ray-hit/set.md)(other: [RayHit](../../com.google.ar.sceneform.collision/-ray-hit/index.md))<br>open fun [set](set.md)(other: [PickHitResult](index.md)) |
| [setDistance](index.md#2065711722%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setDistance](index.md#2065711722%2FFunctions%2F-1571379623)(distance: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setPoint](index.md#1104272604%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setPoint](index.md#1104272604%2FFunctions%2F-1571379623)(point: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [node](node.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [node](node.md): [Node](../../io.github.sceneview.node/-node/index.md) |
