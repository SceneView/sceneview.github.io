//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLBLoader](index.md)

# GLBLoader

[androidJvm]\
object [GLBLoader](index.md)

## Functions

| Name | Summary |
|---|---|
| [createModel](create-model.md) | [androidJvm]<br>fun [createModel](create-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[ModelRenderable](../../com.google.ar.sceneform.rendering/-model-renderable/index.md)&gt; |
| [loadModel](load-model.md) | [androidJvm]<br>suspend fun [loadModel](load-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ModelRenderable](../../com.google.ar.sceneform.rendering/-model-renderable/index.md)? |
| [loadModelAsync](load-model-async.md) | [androidJvm]<br>fun [loadModelAsync](load-model-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html), result: ([ModelRenderable](../../com.google.ar.sceneform.rendering/-model-renderable/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job<br>For Java compatibility usage. |
