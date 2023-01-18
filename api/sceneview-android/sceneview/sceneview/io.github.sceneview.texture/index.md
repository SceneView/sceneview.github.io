//[sceneview](../../index.md)/[io.github.sceneview.texture](index.md)

# Package io.github.sceneview.texture

## Types

| Name | Summary |
|---|---|
| [TextureLoader](-texture-loader/index.md) | [androidJvm]<br>object [TextureLoader](-texture-loader/index.md)<br>Based on the com.google.android.filament.textured.loadTexture |
| [TextureSampler2D](-texture-sampler2-d/index.md) | [androidJvm]<br>class [TextureSampler2D](-texture-sampler2-d/index.md) : TextureSampler |
| [TextureSamplerExternal](-texture-sampler-external/index.md) | [androidJvm]<br>class [TextureSamplerExternal](-texture-sampler-external/index.md) : TextureSampler |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun Stream.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): Stream<br>fun Texture.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): Texture |
| [destroy](destroy.md) | [androidJvm]<br>fun Stream.[destroy](destroy.md)()<br>[androidJvm]<br>fun Texture.[destroy](destroy.md)()<br>Destroys a Texture and frees all its associated resources. |
| [setExternalStream](set-external-stream.md) | [androidJvm]<br>fun Texture.[setExternalStream](set-external-stream.md)(stream: Stream) |
| [setImage](set-image.md) | [androidJvm]<br>fun Texture.[setImage](set-image.md)(level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffer: Texture.PixelBufferDescriptor)<br>fun Texture.[setImage](set-image.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffer: Texture.PixelBufferDescriptor, @[Size](https://developer.android.com/reference/kotlin/androidx/annotation/Size.html)(min = 6)faceOffsetsInBytes: [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html)) |
| [use](use.md) | [androidJvm]<br>fun &lt;[R](use.md)&gt; Stream.[use](use.md)(block: (Stream) -&gt; [R](use.md)): [R](use.md)<br>fun &lt;[R](use.md)&gt; Texture.[use](use.md)(block: (Texture) -&gt; [R](use.md)): [R](use.md) |
