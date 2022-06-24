//[sceneview](../../../index.md)/[io.github.sceneview.material](../index.md)/[MaterialLoader](index.md)/[createMaterial](create-material.md)

# createMaterial

[androidJvm]\
fun [createMaterial](create-material.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): MaterialInstance

###  Load a Material object outside of a coroutine scope from a local filamat file.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.material.MaterialLoader](load-material.md) |  |

[androidJvm]\
fun [createMaterial](create-material.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, filamatBuffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)): MaterialInstance

###  Creates and returns the Material object

The material data is a binary blob produced by libfilamat or by matc.

#### Return

the newly created object

## Parameters

androidJvm

| | |
|---|---|
| filamatBuffer | The content of the Filamat File |
