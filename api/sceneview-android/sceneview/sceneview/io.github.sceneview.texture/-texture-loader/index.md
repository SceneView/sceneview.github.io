//[sceneview](../../../index.md)/[io.github.sceneview.texture](../index.md)/[TextureLoader](index.md)

# TextureLoader

[androidJvm]\
object [TextureLoader](index.md)

Based on the com.google.android.filament.textured.loadTexture

## Types

| Name | Summary |
|---|---|
| [TextureType](-texture-type/index.md) | [androidJvm]<br>enum [TextureType](-texture-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[TextureLoader.TextureType](-texture-type/index.md)&gt; |

## Functions

| Name | Summary |
|---|---|
| [createImageTexture](create-image-texture.md) | [androidJvm]<br>fun [createImageTexture](create-image-texture.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, imageBuffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), type: [TextureLoader.TextureType](-texture-type/index.md) = TextureType.COLOR): Texture |
| [loadImageTexture](load-image-texture.md) | [androidJvm]<br>suspend fun [loadImageTexture](load-image-texture.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), imageFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [TextureLoader.TextureType](-texture-type/index.md) = TextureType.COLOR): Texture? |
| [loadImageTextureAsync](load-image-texture-async.md) | [androidJvm]<br>fun [loadImageTextureAsync](load-image-texture-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), imageFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [TextureLoader.TextureType](-texture-type/index.md) = TextureType.COLOR, result: (Texture?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job |
