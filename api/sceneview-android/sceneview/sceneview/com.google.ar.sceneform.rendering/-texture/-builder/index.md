//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Texture](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)

Factory class for [Texture](../index.md)

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Texture](../index.md)&gt;<br>Creates a new [Texture](../index.md) based on the parameters set previously |
| [setData](set-data.md) | [androidJvm]<br>open fun [setData](set-data.md)(textureInternalData: [TextureInternalData](../../-texture-internal-data/index.md)): [Texture.Builder](index.md)<br>Sets internal data of the texture directly. |
| [setRegistryId](set-registry-id.md) | [androidJvm]<br>open fun [setRegistryId](set-registry-id.md)(registryId: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Texture.Builder](index.md)<br>Allows a [Texture](../index.md) to be reused. |
| [setSampler](set-sampler.md) | [androidJvm]<br>open fun [setSampler](set-sampler.md)(sampler: [Texture.Sampler](../-sampler/index.md)): [Texture.Builder](index.md)<br>Sets the [Sampler](../-sampler/index.md)to control rendering parameters on the [Texture](../index.md). |
| [setSource](set-source.md) | [androidJvm]<br>open fun [setSource](set-source.md)(bitmap: [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)): [Texture.Builder](index.md)<br>Allows a [Texture](../index.md) to be constructed from a [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html).<br>[androidJvm]<br>open fun [setSource](set-source.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [Texture.Builder](index.md)<br>Allows a [Texture](../index.md) to be constructed via callable function.<br>[androidJvm]<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [Texture.Builder](index.md)<br>Allows a [Texture](../index.md) to be constructed from [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html).<br>[androidJvm]<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Texture.Builder](index.md)<br>Allows a [Texture](../index.md) to be constructed from resource. |
| [setUsage](set-usage.md) | [androidJvm]<br>open fun [setUsage](set-usage.md)(usage: [Texture.Usage](../-usage/index.md)): [Texture.Builder](index.md)<br>Mark the [Texture](../index.md) as a containing color, normal or arbitrary data. |
