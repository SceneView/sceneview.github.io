//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[loadModel](load-model.md)

# loadModel

[androidJvm]\
suspend fun [loadModel](load-model.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceResolver(fileLocation, it) }): [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187)?

Loads a [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187) from the contents of a GLB or GLTF file

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](../../../../sceneview_1_0_0/io.github.sceneview.loaders/-model-loader/create-model.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the .glb or .gltf file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
| resourceResolver | Only used for GLTF file. Return a GLTF resource absolute location from a relative file location. The given callback is triggered for each requested resource. |
