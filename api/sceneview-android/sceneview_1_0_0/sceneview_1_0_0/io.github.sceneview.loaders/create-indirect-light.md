//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.loaders](index.md)/[createIndirectLight](create-indirect-light.md)

# createIndirectLight

[androidJvm]\
fun HDRLoader.[createIndirectLight](create-indirect-light.md)(engine: Engine, iblPrefilter: [IBLPrefilter](../io.github.sceneview.utils/-i-b-l-prefilter/index.md), skyboxTexture: Texture, specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, apply: IndirectLight.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): IndirectLight

IndirectLight is used to simulate environment lighting, a form of global illumination

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.createSkyboxTexture](create-skybox-texture.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| skyboxTexture | The reflections cubemap mipmap chain. |
| specularFilter | Generates a prefiltered cubemap SpecularFilter is a GPU based implementation of the specular probe pre-integration filter. ** Launch the heaver computation. Expect 100-100ms on the GPU.** |
| apply | Custom IndirectLight.Builder params |

[androidJvm]\
fun HDRLoader.[createIndirectLight](create-indirect-light.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), skyboxTexture: Texture, specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, apply: IndirectLight.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}): IndirectLight

IndirectLight is used to simulate environment lighting, a form of global illumination

## See also

androidJvm

| | |
|---|---|
| [HDRLoader.createSkyboxTexture](create-skybox-texture.md) |  |
| [HDRLoader.createIndirectLight](create-indirect-light.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| skyboxTexture | The reflections cubemap mipmap chain. |
| specularFilter | Generates a prefiltered cubemap SpecularFilter is a GPU based implementation of the specular probe pre-integration filter. ** Launch the heaver computation. Expect 100-100ms on the GPU.** |
| apply | Custom IndirectLight.Builder params |
