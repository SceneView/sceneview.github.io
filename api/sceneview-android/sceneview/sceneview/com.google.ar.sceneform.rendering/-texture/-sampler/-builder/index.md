//[sceneview](../../../../../index.md)/[com.google.ar.sceneform.rendering](../../../index.md)/[Texture](../../index.md)/[Sampler](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
open class [Builder](index.md)

Builder for constructing Sampler objects.

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(): [Texture.Sampler](../index.md)<br>Construct a Sampler from the properties of the Builder. |
| [setMinMagFilter](set-min-mag-filter.md) | [androidJvm]<br>open fun [setMinMagFilter](set-min-mag-filter.md)(minMagFilter: [Texture.Sampler.MagFilter](../-mag-filter/index.md)): [Texture.Sampler.Builder](index.md)<br>Set both the texture minifying function and magnification function. |
| [setWrapMode](set-wrap-mode.md) | [androidJvm]<br>open fun [setWrapMode](set-wrap-mode.md)(wrapMode: [Texture.Sampler.WrapMode](../-wrap-mode/index.md)): [Texture.Sampler.Builder](index.md)<br>Set the wrap mode for all texture coordinates. |

## Properties

| Name | Summary |
|---|---|
| [magFilter](mag-filter.md) | [androidJvm]<br>private open var [magFilter](mag-filter.md): [Texture.Sampler.MagFilter](../-mag-filter/index.md) |
| [minFilter](min-filter.md) | [androidJvm]<br>private open var [minFilter](min-filter.md): [Texture.Sampler.MinFilter](../-min-filter/index.md) |
| [wrapModeR](wrap-mode-r.md) | [androidJvm]<br>private open var [wrapModeR](wrap-mode-r.md): [Texture.Sampler.WrapMode](../-wrap-mode/index.md) |
| [wrapModeS](wrap-mode-s.md) | [androidJvm]<br>private open var [wrapModeS](wrap-mode-s.md): [Texture.Sampler.WrapMode](../-wrap-mode/index.md) |
| [wrapModeT](wrap-mode-t.md) | [androidJvm]<br>private open var [wrapModeT](wrap-mode-t.md): [Texture.Sampler.WrapMode](../-wrap-mode/index.md) |
