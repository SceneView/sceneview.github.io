//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadIndirectLightAsync](load-indirect-light-async.md)

# loadIndirectLightAsync

[androidJvm]\
fun HDRLoader.[loadIndirectLightAsync](load-indirect-light-async.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, apply: IndirectLight.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}, onResult: (indirectLight: IndirectLight?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

IndirectLight is used to simulate environment lighting, a form of global illumination

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadIndirectLight](load-indirect-light.md) |  |
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
fun KTX1Loader.[loadIndirectLightAsync](load-indirect-light-async.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options(), onResult: (ibl: [IBL](-i-b-l/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

fun KTX1Loader.[loadIndirectLightAsync](load-indirect-light-async.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options(), onResult: (ibl: [IBL](-i-b-l/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

Utility for producing environment resources from precompiled cmgen generated KTX files

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
| onResult | The resulting Filament texture and spherical harmonics from the content of the KTX file or null on failure |
