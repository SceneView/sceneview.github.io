//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[IBLPrefilter](index.md)

# IBLPrefilter

[androidJvm]\
class [IBLPrefilter](index.md)(engine: Engine)

##  IBLPrefilter creates and initializes GPU state common to all environment map filters.

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
| [equirectangularToCubemap](equirectangular-to-cubemap.md) | [androidJvm]<br>fun [equirectangularToCubemap](equirectangular-to-cubemap.md)(equirect: Texture): Texture |
| [specularFilter](specular-filter.md) | [androidJvm]<br>fun [specularFilter](specular-filter.md)(skybox: Texture): Texture<br>SpecularFilter is a GPU based implementation of the specular probe pre-integration filter. |

## Properties

| Name | Summary |
|---|---|
| [context](context.md) | [androidJvm]<br>val [context](context.md): IBLPrefilterContext |
