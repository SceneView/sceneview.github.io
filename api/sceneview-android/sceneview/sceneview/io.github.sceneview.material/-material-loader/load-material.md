//[sceneview](../../../index.md)/[io.github.sceneview.material](../index.md)/[MaterialLoader](index.md)/[loadMaterial](load-material.md)

# loadMaterial

[androidJvm]\
suspend fun [loadMaterial](load-material.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), filamatFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): MaterialInstance?

###  Load a Material object from an filamat file

The material file is a binary blob produced by libfilamat or by matc.

## Parameters

androidJvm

| | |
|---|---|
| filamatFileLocation | the filamat file location.<br>-     A relative file location *materials/mymaterial.filamat* -     An android resource from the res folder *context.getResourceUri(R.raw.mymaterial)* -     A File path *Uri.fromFile(myMaterialFile).path* -     An http or https url *https://mydomain.com/mymaterial.filamat* |
