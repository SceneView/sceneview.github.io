//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[loadModelGltfAsync](load-model-gltf-async.md)

# loadModelGltfAsync

[androidJvm]\
fun [loadModelGltfAsync](load-model-gltf-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), gltfFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), resourceLocationResolver: ([String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) -&gt; [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = { resourceFileName: String -&gt;
            &quot;${gltfFileLocation.substringBeforeLast(&quot;/&quot;)}/$resourceFileName&quot;
        }, autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, scaleToUnits: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: ([Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null): [ModelNode](index.md)

###  Loads a monolithic binary glTF and add it to the Node

## Parameters

androidJvm

| | |
|---|---|
| lifecycle | Provide your lifecycle in order to load your model instantly and to destroy it (and its resources) when the lifecycle goes to destroy state. Otherwise the model loading is done when the parent [SceneView](../../io.github.sceneview/-scene-view/index.md) is attached because it needs a kotlinx.coroutines.CoroutineScope to load and resources will be destroyed when the [SceneView](../../io.github.sceneview/-scene-view/index.md) is. You are responsible of manually destroy this [Node](../-node/index.md) only if you don't provide lifecycle and the node is never attached to a [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| gltfFileLocation | the gltf file location:<br>-     A relative asset file location *models/mymodel.gltf* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.gltf* |
| autoAnimate | Plays the animations automatically if the model has one |
| scaleToUnits | Scale the model to fit a unit cube. Default `null` to keep model original size |
| centerOrigin | Center the model origin to this unit cube position<br>-     `null` = Keep the original model center point -     `Position(x = 0.0f, y = 0.0f, z = 0.0f)` = Center the model horizontally and vertically -     `Position(x = 0.0f, y = -1.0f, z = 0.0f)` = center horizontal | bottom aligned -     `Position(x = -1.0f, y = 1.0f, z = 0.0f)` = left | top aligned -     ... |
