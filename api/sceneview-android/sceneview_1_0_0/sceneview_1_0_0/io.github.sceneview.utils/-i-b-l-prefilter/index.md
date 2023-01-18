//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.utils](../index.md)/[IBLPrefilter](index.md)

# IBLPrefilter

[androidJvm]\
class [IBLPrefilter](index.md)(engine: Engine)

IBLPrefilter creates and initializes GPU state common to all environment map filters

Typically, only one instance per filament Engine of this object needs to exist.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.utils.IBLPrefilterContext |  |

## Constructors

| | |
|---|---|
| [IBLPrefilter](-i-b-l-prefilter.md) | [androidJvm]<br>fun [IBLPrefilter](-i-b-l-prefilter.md)(engine: Engine) |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [equirectangularToCubemap](equirectangular-to-cubemap.md) | [androidJvm]<br>fun [equirectangularToCubemap](equirectangular-to-cubemap.md)(equirect: Texture): Texture<br>Converts an equirectangular image to a cubemap. |
| [specularFilter](specular-filter.md) | [androidJvm]<br>fun [specularFilter](specular-filter.md)(skybox: Texture): Texture<br>Generates a prefiltered cubemap. |

## Properties

| Name | Summary |
|---|---|
| [prefilterContext](prefilter-context.md) | [androidJvm]<br>val [prefilterContext](prefilter-context.md): IBLPrefilterContext<br>Created IBLPrefilterContext, keeping it around if several cubemap will be processed |
