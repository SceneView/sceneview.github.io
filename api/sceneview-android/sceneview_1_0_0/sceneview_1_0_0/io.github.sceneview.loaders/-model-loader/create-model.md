//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[createModel](create-model.md)

# createModel

[androidJvm]\
fun [createModel](create-model.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)): [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187)?

Creates a [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187) from the contents of a GLB or GLTF Buffer

Don't forget to call FilamentAsset.releaseSourceData to free the glTF hierarchy as it is no longer needed:

- 
   Right after creating a [ModelNode](../../io.github.sceneview.nodes/-model-node/index.md) that will retrieve the FilamentAsset.getAnimator
- 
   Not before any call to AssetLoader.createInstance

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.gltfio.AssetLoader |  |

[androidJvm]\
fun [createModel](create-model.md)(assetFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187)?

Creates a [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187) from the contents of a GLB or GLTF asset file

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](../../../../sceneview_1_0_0/io.github.sceneview.loaders/-model-loader/create-model.md) |  |