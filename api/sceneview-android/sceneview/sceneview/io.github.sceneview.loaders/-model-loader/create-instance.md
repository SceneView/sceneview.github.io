//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[createInstance](create-instance.md)

# createInstance

[androidJvm]\
fun [createInstance](create-instance.md)(model: [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623)): [ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)?

Adds a new instance to the asset.

Use this with caution. It is more efficient to pre-allocate a max number of instances, and gradually add them to the scene as needed. Instances can also be &quot;recycled&quot; by removing and re-adding them to the scene.

NOTE: destroyInstance() does not exist because gltfio favors flat arrays for storage of entity lists and instance lists, which would be slow to shift. We also wish to discourage create/destroy churn, as noted above.

This cannot be called after FilamentAsset#releaseSourceData(). Animation is not supported in new instances.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](../../../../sceneview/io.github.sceneview.loaders/-model-loader/create-instanced-model.md) |  |
