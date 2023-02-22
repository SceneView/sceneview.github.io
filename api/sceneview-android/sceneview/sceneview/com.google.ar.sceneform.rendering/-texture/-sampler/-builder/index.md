//[sceneview](../../../../../index.md)/[com.google.ar.sceneform.rendering](../../../index.md)/[Texture](../../index.md)/[Sampler](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
open class [Builder](index.md)

Builder for constructing Sampler objects.

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(): [Texture.Sampler](../index.md)<br>Construct a Sampler from the properties of the Builder. |
| [setMagFilter](set-mag-filter.md) | [androidJvm]<br>open fun [setMagFilter](set-mag-filter.md)(magFilter: [Texture.Sampler.MagFilter](../-mag-filter/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the magnification function used whenever the level-of-detail function determines that the texture should be magnified. |
| [setMinFilter](set-min-filter.md) | [androidJvm]<br>open fun [setMinFilter](set-min-filter.md)(minFilter: [Texture.Sampler.MinFilter](../-min-filter/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the minifying function used whenever the level-of-detail function determines that the texture should be minified. |
| [setMinMagFilter](set-min-mag-filter.md) | [androidJvm]<br>open fun [setMinMagFilter](set-min-mag-filter.md)(minMagFilter: [Texture.Sampler.MagFilter](../-mag-filter/index.md)): [Texture.Sampler.Builder](index.md)<br>Set both the texture minifying function and magnification function. |
| [setWrapMode](set-wrap-mode.md) | [androidJvm]<br>open fun [setWrapMode](set-wrap-mode.md)(wrapMode: [Texture.Sampler.WrapMode](../-wrap-mode/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the wrap mode for all texture coordinates. |
| [setWrapModeR](set-wrap-mode-r.md) | [androidJvm]<br>open fun [setWrapModeR](set-wrap-mode-r.md)(wrapMode: [Texture.Sampler.WrapMode](../-wrap-mode/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the wrap mode for texture coordinate R. |
| [setWrapModeS](set-wrap-mode-s.md) | [androidJvm]<br>open fun [setWrapModeS](set-wrap-mode-s.md)(wrapMode: [Texture.Sampler.WrapMode](../-wrap-mode/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the wrap mode for texture coordinate S. |
| [setWrapModeT](set-wrap-mode-t.md) | [androidJvm]<br>open fun [setWrapModeT](set-wrap-mode-t.md)(wrapMode: [Texture.Sampler.WrapMode](../-wrap-mode/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the wrap mode for texture coordinate T. |
