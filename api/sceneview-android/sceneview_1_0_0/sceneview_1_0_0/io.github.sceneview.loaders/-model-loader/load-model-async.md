//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[loadModelAsync](load-model-async.md)

# loadModelAsync

[androidJvm]\
fun [loadModelAsync](load-model-async.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { ModelLoader.resourceResolver(fileLocation, it) }, onResult: ([Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

Loads a [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-602047187) from the contents of a GLB or GLTF file within a created coroutine scope

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](load-model.md) |  |
