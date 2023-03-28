//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadSkybox](load-skybox.md)

# loadSkybox

[androidJvm]\
suspend fun HDRLoader.[loadSkybox](load-skybox.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): Skybox?

The Skybox is rendered as though it were an infinitely large cube with the camera inside it

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadTexture](load-texture.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | The HDR Image (.hdr) file location |
| options | Loader options |
| apply | Custom Skybox.Builder params |

[androidJvm]\
suspend fun KTX1Loader.[loadSkybox](load-skybox.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options()): Skybox?

Utility for producing environment resources from precompiled cmgen generated KTX files

Consumes the content of KTX files and produces a Skybox

You can generate ktx ibl and skybox files using:

`cmgen --deploy ./output --format=ktx --size=256 --extract-blur=0.1 environment.hdr`

Documentation: [Filament - Bake environment map](https://github.com/google/filament/blob/main/web/docs/tutorial_redball.md#bake-environment-map)

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the KTX Skybox (_skybox.ktx) file location |
| options | Loader options |

[androidJvm]\
suspend fun KTX1Loader.[loadSkybox](load-skybox.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options()): Skybox?

Utility for producing environment resources from precompiled cmgen generated KTX files

## See also

androidJvm

| | |
|---|---|
| [KTX1Loader.loadSkybox](load-skybox.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the KTX Skybox (_skybox.ktx) file location |
| options | Loader options |
