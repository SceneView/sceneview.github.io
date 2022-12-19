//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[loadInstancedModel](load-instanced-model.md)

# loadInstancedModel

[androidJvm]\
suspend fun [loadInstancedModel](load-instanced-model.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceResolver(fileLocation, it) }): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)?&gt;&gt;?

Loads a primary [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623) with one or more [ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)s from the contents of a GLB or GLTF file.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](../../../../sceneview/io.github.sceneview.loaders/-model-loader/create-instanced-model.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| fileLocation | the .glb or .gltf file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
| count | Must be sized to the desired number of instances. If successful, this method will return the array with secondary instances whose resources are shared with the primary asset. |
| resourceResolver | Only used for GLTF file. Return a GLTF resource absolute location from a relative file location. The given callback is triggered for each requested resource. |
