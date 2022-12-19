//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[createInstancedModel](create-instanced-model.md)

# createInstancedModel

[androidJvm]\
fun [createInstancedModel](create-instanced-model.md)(buffer: [Buffer](https://docs.oracle.com/javase/8/docs/api/java/nio/Buffer.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Buffer](https://docs.oracle.com/javase/8/docs/api/java/nio/Buffer.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)?&gt;&gt;?

Creates a primary [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623) with one or more [ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)s from the contents of a GLB or GLTF file.

Don't forget to call FilamentAsset.releaseSourceData to free the glTF hierarchy as it is no longer needed:

- 
   Right after creating a [ModelNode](../../io.github.sceneview.nodes/-model-node/index.md) that will retrieve the FilamentAsset.getAnimator
- 
   Not before any call to AssetLoader.createInstance

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](load-instanced-model.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| count | Must be sized to the desired number of instances. If successful, this method will return the array with secondary instances whose resources are shared with the primary asset. |
