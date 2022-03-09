//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[MaterialInternalDataImpl](index.md)

# MaterialInternalDataImpl

[androidJvm]\
open class [MaterialInternalDataImpl](index.md) : [MaterialInternalData](../-material-internal-data/index.md)

Represents shared data used by [Material](../-material/index.md)s for rendering. The data will be released when all [Material](../-material/index.md)s using this data are finalized.

## Constructors

| | |
|---|---|
| [MaterialInternalDataImpl](-material-internal-data-impl.md) | [androidJvm]<br>open fun [MaterialInternalDataImpl](-material-internal-data-impl.md)(filamentMaterial: Material) |

## Functions

| Name | Summary |
|---|---|
| [release](../../com.google.ar.sceneform.resources/-shared-reference/release.md) | [androidJvm]<br>open fun [release](../../com.google.ar.sceneform.resources/-shared-reference/release.md)() |
| [retain](../../com.google.ar.sceneform.resources/-shared-reference/retain.md) | [androidJvm]<br>open fun [retain](../../com.google.ar.sceneform.resources/-shared-reference/retain.md)() |

## Properties

| Name | Summary |
|---|---|
| [filamentMaterial](filament-material.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [filamentMaterial](filament-material.md): Material |
