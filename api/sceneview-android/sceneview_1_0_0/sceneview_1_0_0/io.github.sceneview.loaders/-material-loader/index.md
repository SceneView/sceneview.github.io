//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[MaterialLoader](index.md)

# MaterialLoader

[androidJvm]\
class [MaterialLoader](index.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))

A Filament Material defines the visual appearance of an object

Materials function as a templates from which MaterialInstances can be spawned.

## Constructors

| | |
|---|---|
| [MaterialLoader](-material-loader.md) | [androidJvm]<br>fun [MaterialLoader](-material-loader.md)(engine: Engine, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |

## Functions

| Name | Summary |
|---|---|
| [createMaterial](create-material.md) | [androidJvm]<br>fun [createMaterial](create-material.md)(payload: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)): Material<br>Creates and returns a Material object<br>[androidJvm]<br>fun [createMaterial](create-material.md)(assetFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Material<br>Creates and returns a Material object from Filamat asset file |
| [createViewMaterial](create-view-material.md) | [androidJvm]<br>fun [createViewMaterial](create-view-material.md)(viewTexture: Texture, unlit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, invertFrontFaceWinding: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): MaterialInstance |
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [destroyMaterial](destroy-material.md) | [androidJvm]<br>fun [destroyMaterial](destroy-material.md)(material: Material) |
| [destroyMaterialInstance](destroy-material-instance.md) | [androidJvm]<br>fun [destroyMaterialInstance](destroy-material-instance.md)(materialInstance: MaterialInstance) |
| [loadMaterial](load-material.md) | [androidJvm]<br>suspend fun [loadMaterial](load-material.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Material?<br>Loads a Material from the contents of a Filamat file |
| [loadMaterialAsync](load-material-async.md) | [androidJvm]<br>fun [loadMaterialAsync](load-material-async.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), onResult: (Material?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job<br>Loads a Material from the contents of a Filamat file within a created coroutine scope. |

## Properties

| Name | Summary |
|---|---|
| [viewLitMaterial](view-lit-material.md) | [androidJvm]<br>val [viewLitMaterial](view-lit-material.md): Material |
| [viewUnlitMaterial](view-unlit-material.md) | [androidJvm]<br>val [viewUnlitMaterial](view-unlit-material.md): Material |
