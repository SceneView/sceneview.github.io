//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[createSkyboxTexture](create-skybox-texture.md)

# createSkyboxTexture

[androidJvm]\
fun HDRLoader.[createSkyboxTexture](create-skybox-texture.md)(iblPrefilter: [IBLPrefilter](../io.github.sceneview.utils/-i-b-l-prefilter/index.md), hdrTexture: Texture): Texture

fun HDRLoader.[createSkyboxTexture](create-skybox-texture.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), hdrTexture: Texture): Texture

Utility for decoding an HDR file and producing a Filament skybox texture

Converts an equirectangular image to a cubemap

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadTexture](load-texture.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| hdrTexture | Texture to convert to a cubemap.<br>-     Can't be null. -     Must be a 2d texture -     Must have equirectangular geometry, that is width == 2*height. -     Must be allocated with all mip levels. -     Must be SAMPLEABLE |
