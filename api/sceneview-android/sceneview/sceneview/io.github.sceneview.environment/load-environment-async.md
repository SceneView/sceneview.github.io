//[sceneview](../../index.md)/[io.github.sceneview.environment](index.md)/[loadEnvironmentAsync](load-environment-async.md)

# loadEnvironmentAsync

[androidJvm]\
fun HDRLoader.[loadEnvironmentAsync](load-environment-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), hdrFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), specularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultSpecularFilter, createSkybox: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = defaultCreateSkybox, result: ([HDREnvironment](-h-d-r-environment/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

###  Utility for decoding and producing environment resources from an HDR file

For Java compatibility usage.

Kotlin developers should use [HDRLoader.loadEnvironment](load-environment.md)

[Documentation](load-environment.md)

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun KTXLoader.[loadEnvironmentAsync](load-environment-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), iblKtxFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), skyboxKtxFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, result: ([Environment](-environment/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

###  Utility for producing environment resources from precompiled cmgen generated KTX files

For Java compatibility usage.

Kotlin developers should use [KTXLoader.loadEnvironment](load-environment.md)
