//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[HDREnvironment](index.md)

# HDREnvironment

[androidJvm]\
open class [HDREnvironment](index.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), cubemap: Texture? = null, indirectLightIrradiance: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null, indirectLightIntensity: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, indirectLightSpecularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultSpecularFilter, createSkybox: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultCreateSkybox, val sharedCubemap: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) : [Environment](../-environment/index.md)

## Constructors

| | |
|---|---|
| [HDREnvironment](-h-d-r-environment.md) | [androidJvm]<br>fun [HDREnvironment](-h-d-r-environment.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), cubemap: Texture? = null, indirectLightIrradiance: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null, indirectLightIntensity: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, indirectLightSpecularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultSpecularFilter, createSkybox: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultCreateSkybox, sharedCubemap: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |

## Functions

| Name | Summary |
|---|---|
| [close](../-environment/close.md) | [androidJvm]<br>open override fun [close](../-environment/close.md)() |
| [destroy](destroy.md) | [androidJvm]<br>open override fun [destroy](destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [cubemap](cubemap.md) | [androidJvm]<br>var [cubemap](cubemap.md): Texture? |
| [indirectLight](../-environment/indirect-light.md) | [androidJvm]<br>val [indirectLight](../-environment/indirect-light.md): IndirectLight? = null<br>Environment lighting has a two components: |
| [indirectLightIntensity](indirect-light-intensity.md) | [androidJvm]<br>var [indirectLightIntensity](indirect-light-intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? |
| [sharedCubemap](shared-cubemap.md) | [androidJvm]<br>val [sharedCubemap](shared-cubemap.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [skybox](../-environment/skybox.md) | [androidJvm]<br>val [skybox](../-environment/skybox.md): Skybox? = null<br>The Skybox to use to fill untouched pixels, or null to unset the Skybox. |
| [sphericalHarmonics](../-environment/spherical-harmonics.md) | [androidJvm]<br>val [sphericalHarmonics](../-environment/spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null |
