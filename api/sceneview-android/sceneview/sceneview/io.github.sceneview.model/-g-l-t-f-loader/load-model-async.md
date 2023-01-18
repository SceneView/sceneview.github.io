//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLTFLoader](index.md)/[loadModelAsync](load-model-async.md)

# loadModelAsync

[androidJvm]\
fun [loadModelAsync](load-model-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), gltfFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceLocationResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceFileName: String -&gt;
            &quot;${gltfFileLocation.substringBeforeLast(&quot;/&quot;)}/$resourceFileName&quot;
        }, result: ([Model](../index.md#1227607086%2FClasslikes%2F-1571379623)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job

###  Utility for loading a glTF 3D model

For Java compatibility usage.

Kotlin developers should use [GLTFLoader.loadModel](load-model.md)

GLTFLoader.loadEnvironment
