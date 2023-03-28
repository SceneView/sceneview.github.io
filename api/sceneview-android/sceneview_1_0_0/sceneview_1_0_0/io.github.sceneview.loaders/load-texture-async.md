//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadTextureAsync](load-texture-async.md)

# loadTextureAsync

[androidJvm]\
fun HDRLoader.[loadTextureAsync](load-texture-async.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), onResult: (texture: Texture?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

fun HDRLoader.[loadTextureAsync](load-texture-async.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), onResult: (texture: Texture?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

Utility for decoding an HDR file and producing a Filament texture

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadTexture](load-texture.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the HDR Image (.hdr) file location |
| options | Loader options |
