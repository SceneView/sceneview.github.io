//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[PickHitResult](index.md)

# PickHitResult

[androidJvm]\
open class [PickHitResult](index.md) : [RayHit](../../com.google.ar.sceneform.collision/-ray-hit/index.md)

Stores the results of calls to Scene.hitTest and Scene.hitTestAll. Contains a node that was hit by the hit test, and associated information.

## Functions

| Name | Summary |
|---|---|
| [reset](reset.md) | [androidJvm]<br>open fun [reset](reset.md)() |
| [set](../../com.google.ar.sceneform.collision/-ray-hit/set.md) | [androidJvm]<br>open fun [set](../../com.google.ar.sceneform.collision/-ray-hit/set.md)(other: [RayHit](../../com.google.ar.sceneform.collision/-ray-hit/index.md))<br>open fun [set](set.md)(other: [PickHitResult](index.md)) |

## Properties

| Name | Summary |
|---|---|
| [distance](../../com.google.ar.sceneform.collision/-ray-hit/distance.md) | [androidJvm]<br>open var [distance](../../com.google.ar.sceneform.collision/-ray-hit/distance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [node](node.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open var [node](node.md): [Node](../../io.github.sceneview.node/-node/index.md) |
| [point](../../com.google.ar.sceneform.collision/-ray-hit/point.md) | [androidJvm]<br>var [point](../../com.google.ar.sceneform.collision/-ray-hit/point.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
