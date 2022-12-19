//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[ModelLoader](index.md)/[loadInstancedModelAsync](load-instanced-model-async.md)

# loadInstancedModelAsync

[androidJvm]\
fun [loadInstancedModelAsync](load-instanced-model-async.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), resourceResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceResolver(fileLocation, it) }, onResult: ([Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)?&gt;&gt;?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

Loads a primary [Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623) with one or more [ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)s from the contents of a GLB or GLTF file with a created coroutine scope.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.loaders.ModelLoader](load-instanced-model.md) |  |
