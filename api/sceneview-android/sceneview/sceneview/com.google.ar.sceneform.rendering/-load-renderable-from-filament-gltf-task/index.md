//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[LoadRenderableFromFilamentGltfTask](index.md)

# LoadRenderableFromFilamentGltfTask

[androidJvm]\
open class [LoadRenderableFromFilamentGltfTask](index.md)&lt;[T](index.md) : [Renderable](../-renderable/index.md)?&gt;

Task for initializing a renderable with glTF data loaded with gltfio.

## Functions

| Name | Summary |
|---|---|
| [downloadAndProcessRenderable](download-and-process-renderable.md) | [androidJvm]<br>open fun [downloadAndProcessRenderable](download-and-process-renderable.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](index.md)&gt;<br>Returns [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html) for a new [Renderable](../-renderable/index.md). |
