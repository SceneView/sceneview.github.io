//[sceneview](../../../index.md)/[com.google.ar.sceneform.resources](../index.md)/[ResourceRegistry](index.md)/[get](get.md)

# get

[androidJvm]\

@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)

open fun [get](get.md)(id: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.rendering/-future-helper/log-on-exception.md)&gt;

Returns a future to a resource previously registered with the same id. If resource has not yet been registered or was garbage collected, returns null. The future may be to a resource that has already finished loading, in which case [isDone](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html#isdone) will be true.
