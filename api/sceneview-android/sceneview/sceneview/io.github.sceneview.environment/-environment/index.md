//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[Environment](index.md)

# Environment

[androidJvm]\
open class [Environment](index.md)(val indirectLight: IndirectLight? = null, val skybox: Skybox? = null, val sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null) : [Closeable](https://developer.android.com/reference/kotlin/java/io/Closeable.html)

###  Indirect light and skybox environment for a scene

Environments are usually captured as high-resolution HDR equirectangular images and processed by the cmgen tool to generate the data needed by IndirectLight.

You can also process an hdr at runtime but this is more consuming.

- 
   Currently IndirectLight is intended to be used for &quot;distant probes&quot;, that is, to represent global illumination from a distant (i.e. at infinity) environment, such as the sky or distant mountains. Only a single IndirectLight can be used in a Scene. This limitation will be lifted in the future.
- 
   When added to a Scene, the Skybox fills all untouched pixels.

Defines the lighting environment and the skybox for the scene

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.IndirectLight |  |
| [KTXLoader.loadEnvironment](../load-environment.md) |  |
| [HDRLoader.loadEnvironment](../load-environment.md) |  |

## Constructors

| | |
|---|---|
| [Environment](-environment.md) | [androidJvm]<br>fun [Environment](-environment.md)(indirectLight: IndirectLight? = null, skybox: Skybox? = null, sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [androidJvm]<br>open override fun [close](close.md)() |
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)()<br>You shouldn't have to call it if you used lifecycle, since each entity is destroyed at the onDestroy() |

## Properties

| Name | Summary |
|---|---|
| [indirectLight](indirect-light.md) | [androidJvm]<br>val [indirectLight](indirect-light.md): IndirectLight? = null<br>Environment lighting has a two components: |
| [skybox](skybox.md) | [androidJvm]<br>val [skybox](skybox.md): Skybox? = null<br>The Skybox to use to fill untouched pixels, or null to unset the Skybox. |
| [sphericalHarmonics](spherical-harmonics.md) | [androidJvm]<br>val [sphericalHarmonics](spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)? = null |

## Inheritors

| Name |
|---|
| [HDREnvironment](../-h-d-r-environment/index.md) |
| [KTXEnvironment](../-k-t-x-environment/index.md) |
