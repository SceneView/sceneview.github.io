//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLTFLoader](index.md)

# GLTFLoader

[androidJvm]\
object [GLTFLoader](index.md)

## Functions

| Name | Summary |
|---|---|
| [createModel](create-model.md) | [androidJvm]<br>suspend fun [createModel](create-model.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), resourceBufferResolver: suspend ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): [Model](../index.md#1227607086%2FClasslikes%2F-1571379623)? |
| [loadModel](load-model.md) | [androidJvm]<br>suspend fun [loadModel](load-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), gltfFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceLocationResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceFileName: String -&gt;             &quot;${gltfFileLocation.substringBeforeLast(&quot;/&quot;)}/$resourceFileName&quot;         }, lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): [Model](../index.md#1227607086%2FClasslikes%2F-1571379623)? |
| [loadModelAsync](load-model-async.md) | [androidJvm]<br>fun [loadModelAsync](load-model-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), gltfFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceLocationResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceFileName: String -&gt;             &quot;${gltfFileLocation.substringBeforeLast(&quot;/&quot;)}/$resourceFileName&quot;         }, result: ([Model](../index.md#1227607086%2FClasslikes%2F-1571379623)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job<br>For Java compatibility usage. |
