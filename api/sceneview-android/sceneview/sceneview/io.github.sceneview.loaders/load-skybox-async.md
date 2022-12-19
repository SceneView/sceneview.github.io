//[sceneview](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadSkyboxAsync](load-skybox-async.md)

# loadSkyboxAsync

[androidJvm]\
fun HDRLoader.[loadSkyboxAsync](load-skybox-async.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), apply: Skybox.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}, onResult: (skybox: Skybox?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

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
fun KTX1Loader.[loadSkyboxAsync](load-skybox-async.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options(), onResult: (skybox: Skybox?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

fun KTX1Loader.[loadSkyboxAsync](load-skybox-async.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: KTX1Loader.Options = KTX1Loader.Options(), onResult: (skybox: Skybox?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

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
