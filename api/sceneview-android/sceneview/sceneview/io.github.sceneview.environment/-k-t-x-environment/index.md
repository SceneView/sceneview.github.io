//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[KTXEnvironment](index.md)

# KTXEnvironment

[androidJvm]\
class [KTXEnvironment](index.md)(val indirectLight: IndirectLight?, val skybox: Skybox? = null, val sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null) : [Environment](../-environment/index.md)

## Constructors

| | |
|---|---|
| [KTXEnvironment](-k-t-x-environment.md) | [androidJvm]<br>fun [KTXEnvironment](-k-t-x-environment.md)(indirectLight: IndirectLight?, skybox: Skybox? = null, sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [close](../-environment/close.md) | [androidJvm]<br>open override fun [close](../-environment/close.md)() |
| [destroy](../-environment/destroy.md) | [androidJvm]<br>open fun [destroy](../-environment/destroy.md)()<br>You shouldn't have to call it if you used lifecycle, since each entity is destroyed at the onDestroy() |

## Properties

| Name | Summary |
|---|---|
| [indirectLight](../-environment/indirect-light.md) | [androidJvm]<br>val [indirectLight](../-environment/indirect-light.md): IndirectLight? = null<br>Environment lighting has a two components: |
| [skybox](../-environment/skybox.md) | [androidJvm]<br>val [skybox](../-environment/skybox.md): Skybox? = null<br>The Skybox to use to fill untouched pixels, or null to unset the Skybox. |
| [sphericalHarmonics](../-environment/spherical-harmonics.md) | [androidJvm]<br>val [sphericalHarmonics](../-environment/spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null |
