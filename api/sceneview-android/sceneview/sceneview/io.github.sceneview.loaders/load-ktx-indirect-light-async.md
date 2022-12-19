//[sceneview](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadKtxIndirectLightAsync](load-ktx-indirect-light-async.md)

# loadKtxIndirectLightAsync

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[loadKtxIndirectLightAsync](load-ktx-indirect-light-async.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options(), onResult: (ibl: [IBL](-i-b-l/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null): Job

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
