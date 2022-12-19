//[sceneview](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadIndirectLight](load-indirect-light.md)

# loadIndirectLight

[androidJvm]\
suspend fun HDRLoader.[loadIndirectLight](load-indirect-light.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, apply: IndirectLight.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): IndirectLight?

IndirectLight is used to simulate environment lighting, a form of global illumination

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadTexture](load-texture.md) |  |
| [HDRLoader.createIndirectLight](create-indirect-light.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | The HDR Image (.hdr) file location |
| options | Loader options |
| specularFilter | Generates a prefiltered cubemap SpecularFilter is a GPU based implementation of the specular probe pre-integration filter. ** Launch the heaver computation. Expect 100-100ms on the GPU.** |
| apply | Custom IndirectLight.Builder params |

[androidJvm]\
suspend fun KTX1Loader.[loadIndirectLight](load-indirect-light.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options()): [IBL](-i-b-l/index.md)?

Utility for producing environment resources from precompiled cmgen generated KTX files

Consumes the content of KTX files and produces an [IBL](-i-b-l/index.md) containing an IndirectLight and Spherical Harmonics.

You can generate ktx ibl and skybox files using:

`cmgen --deploy ./output --format=ktx --size=256 --extract-blur=0.1 environment.hdr`

Documentation: [Filament - Bake environment map](https://github.com/google/filament/blob/main/web/docs/tutorial_redball.md#bake-environment-map)

#### Return

The resulting Filament texture and spherical harmonics from the content of the KTX file or null on failure

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the KTX Image Bases Light (_ibl.ktx) file location |
| options | Loader options |

[androidJvm]\
suspend fun KTX1Loader.[loadIndirectLight](load-indirect-light.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options()): [IBL](-i-b-l/index.md)?

Utility for producing environment resources from precompiled cmgen generated KTX files

#### Return

The resulting Filament texture and spherical harmonics from the content of the KTX file or null on failure

## See also

androidJvm

| | |
|---|---|
| [KTX1Loader.loadIndirectLight](load-indirect-light.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the KTX Image Bases Light (_ibl.ktx) file location |
| options | Loader options |
