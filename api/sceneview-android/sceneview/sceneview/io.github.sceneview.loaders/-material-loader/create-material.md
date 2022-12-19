//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[MaterialLoader](index.md)/[createMaterial](create-material.md)

# createMaterial

[androidJvm]\
fun [createMaterial](create-material.md)(payload: [Buffer](https://docs.oracle.com/javase/8/docs/api/java/nio/Buffer.html)): Material

Creates and returns a Material object

A Filament Material defines the visual appearance of an object. Materials function as a templates from which MaterialInstances can be spawned.

Documentation: [Filament Materials Guide](https://google.github.io/filament/Materials.html)

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.MaterialLoader](load-material.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| payload | Specifies the material data. The material data is a binary blob produced by libfilamat or by matc. |

[androidJvm]\
fun [createMaterial](create-material.md)(assetFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Material

Creates and returns a Material object from Filamat asset file

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.MaterialLoader](create-material.md) |  |
