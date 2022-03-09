//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Material](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)

Builder for constructing a [Material](../index.md)

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../index.md)&gt;<br>Creates a new [Material](../index.md) based on the parameters set previously. |
| [setSource](set-source.md) | [androidJvm]<br>open fun [setSource](set-source.md)(materialBuffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Material.Builder](index.md)<br>Allows a [Material](../index.md) to be created with data.<br>[androidJvm]<br>open fun [setSource](set-source.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [Material.Builder](index.md)<br>Allows a [Material](../index.md) to be constructed via callable function.<br>[androidJvm]<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [Material.Builder](index.md)<br>Allows a [Material](../index.md) to be constructed from [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html).<br>[androidJvm]<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Material.Builder](index.md)<br>Allows a [Material](../index.md) to be constructed from resource. |

## Properties

| Name | Summary |
|---|---|
| [cleanupResource](cleanup-resource.md) | [androidJvm]<br>private open var [cleanupResource](cleanup-resource.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [registryId](registry-id.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [registryId](registry-id.md): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
