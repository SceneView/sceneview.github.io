//[sceneview](../../../index.md)/[com.google.ar.sceneform.collision](../index.md)/[Collider](index.md)

# Collider

[androidJvm]\
open class [Collider](index.md)

Represents the collision information associated with a transformation that can be attached to the collision system. Not publicly exposed.

## Constructors

| | |
|---|---|
| [Collider](-collider.md) | [androidJvm]<br>open fun [Collider](-collider.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md), localCollisionShape: [CollisionShape](../-collision-shape/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getShape](get-shape.md) | [androidJvm]<br>open fun [getShape](get-shape.md)(): [CollisionShape](../-collision-shape/index.md) |
| [getTransformedShape](get-transformed-shape.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getTransformedShape](get-transformed-shape.md)(): [CollisionShape](../-collision-shape/index.md) |
| [markWorldShapeDirty](mark-world-shape-dirty.md) | [androidJvm]<br>open fun [markWorldShapeDirty](mark-world-shape-dirty.md)() |
| [setShape](set-shape.md) | [androidJvm]<br>open fun [setShape](set-shape.md)(localCollisionShape: [CollisionShape](../-collision-shape/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [attachedCollisionSystem](attached-collision-system.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [attachedCollisionSystem](attached-collision-system.md): [CollisionSystem](../-collision-system/index.md) |
| [transformProvider](transform-provider.md) | [androidJvm]<br>private open val [transformProvider](transform-provider.md): [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md) |
