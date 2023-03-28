//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLBLoader](index.md)

# GLBLoader

[androidJvm]\
object [GLBLoader](index.md)

## Functions

| Name | Summary |
|---|---|
| [createModel](create-model.md) | [androidJvm]<br>fun [createModel](create-model.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html)): [Model](../index.md#1227607086%2FClasslikes%2F-1571379623)? |
| [loadInstancedModel](load-instanced-model.md) | [androidJvm]<br>suspend fun [loadInstancedModel](load-instanced-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Model](../index.md#1227607086%2FClasslikes%2F-1571379623), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelInstance](../index.md#1724271641%2FClasslikes%2F-1571379623)?&gt;&gt;?<br>Consumes the contents of a glTF 2.0 file and produces a primary asset with one or more instances. |
| [loadModel](load-model.md) | [androidJvm]<br>suspend fun [loadModel](load-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Model](../index.md#1227607086%2FClasslikes%2F-1571379623)? |
| [loadModelAsync](load-model-async.md) | [androidJvm]<br>fun [loadModelAsync](load-model-async.md)(coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), result: ([Model](../index.md#1227607086%2FClasslikes%2F-1571379623)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job<br>For Java compatibility usage. |
