//[sceneview](../../../index.md)/[com.google.ar.sceneform.resources](../index.md)/[ResourceRegistry](index.md)

# ResourceRegistry

[androidJvm]\
open class [ResourceRegistry](index.md)&lt;[T](index.md)&gt; : [ResourceHolder](../-resource-holder/index.md)

ResourceRegistry keeps track of resources that have been loaded and are in the process of being loaded. The registry maintains only weak references and doesn't prevent resources from being collected.

## Functions

| Name | Summary |
|---|---|
| [destroyAllResources](destroy-all-resources.md) | [androidJvm]<br>open fun [destroyAllResources](destroy-all-resources.md)()<br>Removes all cache entries. |
| [get](get.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [get](get.md)(id: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;<br>Returns a future to a resource previously registered with the same id. |
| [reclaimReleasedResources](reclaim-released-resources.md) | [androidJvm]<br>open fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Polls for garbage collected objects and disposes associated data. |
| [register](register.md) | [androidJvm]<br>open fun [register](register.md)(id: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), futureResource: [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;)<br>Registers a future to a resource by an id. |
