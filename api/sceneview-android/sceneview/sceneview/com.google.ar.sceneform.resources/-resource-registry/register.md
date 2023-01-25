//[sceneview](../../../index.md)/[com.google.ar.sceneform.resources](../index.md)/[ResourceRegistry](index.md)/[register](register.md)

# register

[androidJvm]\
open fun [register](register.md)(id: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), futureResource: [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](index.md)&gt;)

Registers a future to a resource by an id. If registering a resource that has already finished loading, use [completedFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html#completedfuture).
