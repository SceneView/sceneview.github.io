//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[ModelNode](-model-node.md)

# ModelNode

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [ModelNode](-model-node.md)(position: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = DEFAULT_POSITION, rotation: [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623) = DEFAULT_ROTATION, scale: [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623) = DEFAULT_SCALE)

###  Construct a [ModelNode](index.md) with it Position, Rotation and Scale

## Parameters

androidJvm

| | |
|---|---|
| position | See [Node.position](../-node/position.md) |
| rotation | See [Node.rotation](../-node/rotation.md) |
| scale | See [Node.scale](../-node/scale.md) |

[androidJvm]\
fun [ModelNode](-model-node.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, modelFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, scaleUnits: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: ([Model](../../io.github.sceneview.model/index.md#1227607086%2FClasslikes%2F-1571379623)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

###  Create the Node and load a monolithic binary glTF and add it to the Node

## Parameters

androidJvm

| | |
|---|---|
| lifecycle | Provide your lifecycle in order to load your model instantly and to destroy it (and its resources) when the lifecycle goes to destroy state. Passing null means the model loading will be done when the Node is added to the SceneView and the destroy will be done when the SceneView is detached. Otherwise the model loading is done when the parent [SceneView](../../io.github.sceneview/-scene-view/index.md) is attached because it needs a kotlinx.coroutines.CoroutineScope to load and resources will be destroyed when the [SceneView](../../io.github.sceneview/-scene-view/index.md) is. You are responsible of manually destroy this [Node](../-node/index.md) only if you don't provide lifecycle and the node is never attached to a [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| modelFileLocation | the model glb/gltf file location:<br>- A relative asset file location *models/mymodel.glb*<br>- An Android resource from the res folder *context.getResourceUri(R.raw.mymodel)*<br>- A File path *Uri.fromFile(myModelFile).path*<br>- An http or https url *https://mydomain.com/mymodel.glb* |
| autoAnimate | Plays the animations automatically if the model has one |
| scaleUnits | Scale the model to fit a unit cube. Default null to keep model original size |
| centerOrigin | Center point origin position within the model: Float cube position values between -1.0 and 1.0 corresponding to percents from model sizes.<br>-     null = Keep the origin point where it was at the model export time -     Position(x = 0.0f, y = 0.0f, z = 0.0f) = Center the model horizontally and vertically -     Position(x = 0.0f, y = -1.0f, z = 0.0f) = center horizontal | bottom -     Position(x = -1.0f, y = 1.0f, z = 0.0f) = left | top -     ...<br>@param onError An exception has been thrown during model loading<br>@param onLoaded Called when the model loading finished so you can change its properties<br>(material, texture,...)<br>@see loadModel |
