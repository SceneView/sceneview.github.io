//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLTFLoader](index.md)/[loadModel](load-model.md)

# loadModel

[androidJvm]\
suspend fun [loadModel](load-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), gltfFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceLocationResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceFileName: String -&gt;
            &quot;${gltfFileLocation.substringBeforeLast(&quot;/&quot;)}/$resourceFileName&quot;
        }, lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): [Model](../index.md#1227607086%2FClasslikes%2F-1571379623)?

###  Utility for loading a glTF 3D model

## Parameters

androidJvm

| | |
|---|---|
| gltfFileLocation | the gltf file location:<br>-     A relative asset file location *models/mymodel.gltf* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.gltf* |
