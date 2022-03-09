//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[HDREnvironment](index.md)

# HDREnvironment

[androidJvm]\
open class [HDREnvironment](index.md)(cubemap: Texture?, irradiance: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)?, intensity: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)?, skyboxEnvironment: Texture?, specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Environment](../-environment/index.md)

## Functions

| Name | Summary |
|---|---|
| [close](../-environment/close.md) | [androidJvm]<br>open override fun [close](../-environment/close.md)() |
| [destroy](destroy.md) | [androidJvm]<br>open override fun [destroy](destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [cubemap](cubemap.md) | [androidJvm]<br>var [cubemap](cubemap.md): Texture? |
| [indirectLight](../-environment/indirect-light.md) | [androidJvm]<br>var [indirectLight](../-environment/indirect-light.md): IndirectLight?<br>Environment lighting has a two components: |
| [intensity](intensity.md) | [androidJvm]<br>var [intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? |
| [sharedCubemap](shared-cubemap.md) | [androidJvm]<br>var [sharedCubemap](shared-cubemap.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [skybox](../-environment/skybox.md) | [androidJvm]<br>var [skybox](../-environment/skybox.md): Skybox?<br>The Skybox to use to fill untouched pixels, or null to unset the Skybox. |
| [skyboxEnvironment](skybox-environment.md) | [androidJvm]<br>var [skyboxEnvironment](skybox-environment.md): Texture? |
| [sphericalHarmonics](../-environment/spherical-harmonics.md) | [androidJvm]<br>var [sphericalHarmonics](../-environment/spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? |
