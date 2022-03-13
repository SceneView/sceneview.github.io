//[sceneview](../../../index.md)/[io.github.sceneview.material](../index.md)/[MaterialLoader](index.md)/[loadMaterialAsync](load-material-async.md)

# loadMaterialAsync

[androidJvm]\
fun [loadMaterialAsync](load-material-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html), result: (MaterialInstance?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

###  Load a Material object from an filamat file

The material file is a binary blob produced by libfilamat or by matc.

For Java compatibility usage.

Kotlin developers should use HDRLoader.loadEnvironment

[See](load-material.md)