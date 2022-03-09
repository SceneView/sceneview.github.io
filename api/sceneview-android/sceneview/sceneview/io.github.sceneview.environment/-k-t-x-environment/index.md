//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[KTXEnvironment](index.md)

# KTXEnvironment

[androidJvm]\
class [KTXEnvironment](index.md)(indirectLight: IndirectLight?, skybox: Skybox?, sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)?) : [Environment](../-environment/index.md)

## Functions

| Name | Summary |
|---|---|
| [close](../-environment/close.md) | [androidJvm]<br>open override fun [close](../-environment/close.md)() |
| [destroy](../-environment/destroy.md) | [androidJvm]<br>open fun [destroy](../-environment/destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [indirectLight](../-environment/indirect-light.md) | [androidJvm]<br>var [indirectLight](../-environment/indirect-light.md): IndirectLight?<br>Environment lighting has a two components: |
| [skybox](../-environment/skybox.md) | [androidJvm]<br>var [skybox](../-environment/skybox.md): Skybox?<br>The Skybox to use to fill untouched pixels, or null to unset the Skybox. |
| [sphericalHarmonics](../-environment/spherical-harmonics.md) | [androidJvm]<br>var [sphericalHarmonics](../-environment/spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? |
