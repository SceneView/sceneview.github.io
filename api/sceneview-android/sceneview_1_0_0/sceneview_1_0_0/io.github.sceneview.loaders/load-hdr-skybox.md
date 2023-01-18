//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadHdrSkybox](load-hdr-skybox.md)

# loadHdrSkybox

[androidJvm]\
suspend fun [SceneView](../io.github.sceneview/-scene-view/index.md).[loadHdrSkybox](load-hdr-skybox.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): Skybox?

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
