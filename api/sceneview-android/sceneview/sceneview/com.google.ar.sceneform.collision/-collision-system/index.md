//[sceneview](../../../index.md)/[com.google.ar.sceneform.collision](../index.md)/[CollisionSystem](index.md)

# CollisionSystem

[androidJvm]\
open class [CollisionSystem](index.md)

Manages all of the colliders within a scene.

## Functions

| Name | Summary |
|---|---|
| [addCollider](add-collider.md) | [androidJvm]<br>open fun [addCollider](add-collider.md)(collider: [Collider](../-collider/index.md)) |
| [intersects](intersects.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [intersects](intersects.md)(collider: [Collider](../-collider/index.md)): [Collider](../-collider/index.md) |
| [intersectsAll](intersects-all.md) | [androidJvm]<br>open fun [intersectsAll](intersects-all.md)(collider: [Collider](../-collider/index.md), processResult: [Consumer](https://developer.android.com/reference/kotlin/java/util/function/Consumer.html)&lt;[Collider](../-collider/index.md)&gt;) |
| [raycast](raycast.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [raycast](raycast.md)(ray: [Ray](../-ray/index.md), resultHit: [RayHit](../-ray-hit/index.md), selectableOnly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Collider](../-collider/index.md) |
| [raycastAll](raycast-all.md) | [androidJvm]<br>open fun &lt;[T](raycast-all.md) : [RayHit](../-ray-hit/index.md)?&gt; [raycastAll](raycast-all.md)(ray: [Ray](../-ray/index.md), resultBuffer: [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)processResult: [BiConsumer](https://developer.android.com/reference/kotlin/java/util/function/BiConsumer.html)&lt;[T](../../com.google.ar.sceneform.resources/-resource-registry/index.md), [Collider](../-collider/index.md)&gt;, allocateResult: [Supplier](https://developer.android.com/reference/kotlin/java/util/function/Supplier.html)&lt;[T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)&gt;): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [removeCollider](remove-collider.md) | [androidJvm]<br>open fun [removeCollider](remove-collider.md)(collider: [Collider](../-collider/index.md)) |
