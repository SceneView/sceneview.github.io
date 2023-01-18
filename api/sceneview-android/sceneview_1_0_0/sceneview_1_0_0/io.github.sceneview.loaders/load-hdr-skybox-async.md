//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadHdrSkyboxAsync](load-hdr-skybox-async.md)

# loadHdrSkyboxAsync

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[loadHdrSkyboxAsync](load-hdr-skybox-async.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}, onResult: (skybox: Skybox?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): Job

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
