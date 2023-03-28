//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[loadHdrIndirectLight](load-hdr-indirect-light.md)

# loadHdrIndirectLight

[androidJvm]\
suspend fun [SceneView](../io.github.sceneview/-scene-view/index.md).[loadHdrIndirectLight](load-hdr-indirect-light.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), options: HDRLoader.Options = HDRLoader.Options(), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, apply: IndirectLight.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): IndirectLight?

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