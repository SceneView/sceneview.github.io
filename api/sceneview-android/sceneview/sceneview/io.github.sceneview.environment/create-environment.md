//[sceneview](../../index.md)/[io.github.sceneview.environment](index.md)/[createEnvironment](create-environment.md)

# createEnvironment

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun HDRLoader.[createEnvironment](create-environment.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), hdrBuffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultSpecularFilter, createSkybox: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultCreateSkybox): [HDREnvironment](-h-d-r-environment/index.md)?

###  Utility for decoding and producing environment resources from an HDR file

Consumes the content of an HDR file and produces an IndirectLight and a Skybox.

#### Return

the generated environment indirect light and skybox from the hdr

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.utils.HDRLoader |  |

## Parameters

androidJvm

| | |
|---|---|
| hdrBuffer | The content of the HDR File |
| iblFilter | A filter to apply to the resulting indirect light reflexions texture. Default generates a specular prefiltered cubemap reflection texture. |

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun KTX1Loader.[createEnvironment](create-environment.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), iblKtxBuffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)?, skyboxKtxBuffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)? = null): [KTXEnvironment](-k-t-x-environment/index.md)

###  Utility for producing environment resources from precompiled cmgen generated KTX files

Consumes the content of KTX files and produces an IndirectLight, SphericalHarmonics and a Skybox

You can generate ktx ibl and skybox files using:

cmgen --deploy ./output --format=ktx --size=256 --extract-blur=0.1 environment.hdr

Documentation: [Filament - Bake environment map](https://github.com/google/filament/blob/main/web/docs/tutorial_redball.md#bake-environment-map)

#### Return

the generated environment indirect light, sphericalHarmonics and skybox from the ktxs.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.utils.KTX1Loader |  |

## Parameters

androidJvm

| | |
|---|---|
| iblKtxBuffer | The content of the ibl KTX File. |
| skyboxKtxBuffer | The content of the skybox KTX File. |
