//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadKtxIndirectLight](load-ktx-indirect-light.md)

# loadKtxIndirectLight

[androidJvm]\
suspend fun [SceneView](../io.github.sceneview/-scene-view/index.md).[loadKtxIndirectLight](load-ktx-indirect-light.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options()): [IBL](-i-b-l/index.md)?

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
