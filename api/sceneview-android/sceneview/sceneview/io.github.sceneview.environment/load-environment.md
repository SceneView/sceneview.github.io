//[sceneview](../../index.md)/[io.github.sceneview.environment](index.md)/[loadEnvironment](load-environment.md)

# loadEnvironment

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

suspend fun HDRLoader.[loadEnvironment](load-environment.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), hdrFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultSpecularFilter, createSkybox: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultCreateSkybox): [HDREnvironment](-h-d-r-environment/index.md)?

###  Utility for decoding and producing environment resources from an HDR file

[Documentation](create-environment.md)

#### Return

[Documentation](create-environment.md)

## Parameters

androidJvm

| | |
|---|---|
| hdrFileLocation | the hdr file location. See [Documentation](../io.github.sceneview.utils/file-buffer.md) |
| iblFilter | See [Documentation](create-environment.md) |

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

suspend fun KTXLoader.[loadEnvironment](load-environment.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), iblKtxFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), skyboxKtxFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [Environment](-environment/index.md)

###  Utility for producing environment resources from precompiled cmgen generated KTX files

[Documentation](create-environment.md)

#### Return

[KTXLoader.createEnvironment](create-environment.md)

## Parameters

androidJvm

| | |
|---|---|
| iblKtxFileLocation | the ibl file location [Documentation](../io.github.sceneview.utils/file-buffer.md) |
| skyboxKtxFileLocation | the skybox file location [Documentation](../io.github.sceneview.utils/file-buffer.md) |
