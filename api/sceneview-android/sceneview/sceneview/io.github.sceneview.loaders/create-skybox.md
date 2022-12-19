//[sceneview](../../index.md)/[io.github.sceneview.loaders](index.md)/[createSkybox](create-skybox.md)

# createSkybox

[androidJvm]\
fun HDRLoader.[createSkybox](create-skybox.md)(engine: Engine, skyboxTexture: Texture, apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): Skybox

fun HDRLoader.[createSkybox](create-skybox.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), skyboxTexture: Texture, apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): Skybox

The Skybox is rendered as though it were an infinitely large cube with the camera inside it

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.loadTexture](load-texture.md) |  |
| [HDRLoader.createSkyboxTexture](create-skybox-texture.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| skyboxTexture | The environment map (i.e. the skybox content) |
| apply | Custom Skybox.Builder params |
