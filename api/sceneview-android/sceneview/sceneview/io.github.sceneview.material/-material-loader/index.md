//[sceneview](../../../index.md)/[io.github.sceneview.material](../index.md)/[MaterialLoader](index.md)

# MaterialLoader

[androidJvm]\
object [MaterialLoader](index.md)

## Functions

| Name | Summary |
|---|---|
| [createMaterial](create-material.md) | [androidJvm]<br>fun [createMaterial](create-material.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, filamatBuffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)): MaterialInstance<br>The material data is a binary blob produced by libfilamat or by matc.<br>[androidJvm]<br>fun [createMaterial](create-material.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): MaterialInstance |
| [loadMaterial](load-material.md) | [androidJvm]<br>suspend fun [loadMaterial](load-material.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): MaterialInstance?<br>The material file is a binary blob produced by libfilamat or by matc. |
| [loadMaterialAsync](load-material-async.md) | [androidJvm]<br>fun [loadMaterialAsync](load-material-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), result: (MaterialInstance?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job<br>The material file is a binary blob produced by libfilamat or by matc. |
