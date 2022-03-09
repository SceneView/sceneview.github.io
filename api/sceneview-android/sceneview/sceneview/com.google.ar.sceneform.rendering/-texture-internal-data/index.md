//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[TextureInternalData](index.md)

# TextureInternalData

[androidJvm]\
open class [TextureInternalData](index.md) : [SharedReference](../../com.google.ar.sceneform.resources/-shared-reference/index.md)

Represents shared data used by [Texture](../-texture/index.md)s for rendering. The data will be released when all [Texture](../-texture/index.md)s using this data are finalized.

## Constructors

| | |
|---|---|
| [TextureInternalData](-texture-internal-data.md) | [androidJvm]<br>open fun [TextureInternalData](-texture-internal-data.md)(filamentTexture: Texture, sampler: [Texture.Sampler](../-texture/-sampler/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [release](../../com.google.ar.sceneform.resources/-shared-reference/release.md) | [androidJvm]<br>open fun [release](../../com.google.ar.sceneform.resources/-shared-reference/release.md)() |
| [retain](../../com.google.ar.sceneform.resources/-shared-reference/retain.md) | [androidJvm]<br>open fun [retain](../../com.google.ar.sceneform.resources/-shared-reference/retain.md)() |
