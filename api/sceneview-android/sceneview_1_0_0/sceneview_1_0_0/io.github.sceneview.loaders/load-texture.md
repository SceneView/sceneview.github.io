//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadTexture](load-texture.md)

# loadTexture

[androidJvm]\
suspend fun HDRLoader.[loadTexture](load-texture.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options()): Texture?

Utility for decoding an HDR file and producing a Filament texture

Consumes the content of an HDR file and produces a Texture object.

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the HDR Image (.hdr) file location |
| options | Loader options |

[androidJvm]\
suspend fun HDRLoader.[loadTexture](load-texture.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options()): Texture?

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
