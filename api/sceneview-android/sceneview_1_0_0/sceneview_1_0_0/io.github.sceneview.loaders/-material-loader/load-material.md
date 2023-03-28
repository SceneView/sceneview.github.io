//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[MaterialLoader](index.md)/[loadMaterial](load-material.md)

# loadMaterial

[androidJvm]\
suspend fun [loadMaterial](load-material.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Material?

Loads a Material from the contents of a Filamat file

The material data is a binary blob produced by libfilamat or by matc.

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the .filamat file location:<br>-     A relative asset file location *materials/mymaterial.filamat* -     An Android resource from the res folder *context.getResourceUri(R.raw.mymaterial)* -     A File path *Uri.fromFile(myMaterialFile).path* -     An http or https url *https://mydomain.com/mymaterial.filamat* |
