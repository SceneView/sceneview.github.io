//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[ArModelNode](-ar-model-node.md)

# ArModelNode

[androidJvm]\
fun [ArModelNode](-ar-model-node.md)(placementMode: [PlacementMode](../-placement-mode/index.md) = DEFAULT_PLACEMENT_MODE, hitPosition: [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md) = DEFAULT_HIT_POSITION, followHitPosition: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, instantAnchor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

###  Create an AR positioned 3D model node

## Parameters

androidJvm

| | |
|---|---|
| placementMode | See [placementMode](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/[60]init[62].md) |
| hitPosition | See [hitPosition](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/[60]init[62].md) |
| followHitPosition | See [followHitPosition](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/[60]init[62].md) |
| instantAnchor | See [instantAnchor](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/[60]init[62].md) |

[androidJvm]\
fun [ArModelNode](-ar-model-node.md)(hitResult: HitResult)

TODO : Doc

[androidJvm]\
fun [ArModelNode](-ar-model-node.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, modelGlbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, scaleToUnits: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, centerOrigin: [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: ([Model](../../../../sceneview/io.github.sceneview.model/-model/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

###  Create the Node and load a monolithic binary glTF and add it to the Node

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.node.ArModelNode](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/load-model-glb.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| lifecycle | Provide your lifecycle in order to load your model instantly and to destroy it (and its resources) when the lifecycle goes to destroy state. Otherwise the model loading is done when the parent [SceneView](../../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md) is attached because it needs a kotlinx.coroutines.CoroutineScope to load and resources will be destroyed when the [SceneView](../../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md) is. You are responsible of manually destroy this [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md) only if you don't provide lifecycle and the node is never attached to a [SceneView](../../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md) |
| modelGlbFileLocation | the glb file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
| autoAnimate | Plays the animations automatically if the model has one |
| scaleToUnits | Scale the model to fit a unit cube. Default `null` to keep model original size |
| centerOrigin | Center the model origin to this unit cube position<br>-     `null` = Keep the original model center point -     `Position(x = 0.0f, y = 0.0f, z = 0.0f)` = Center the model horizontally and vertically -     `Position(x = 0.0f, y = -1.0f, z = 0.0f)` = center horizontal | bottom aligned -     `Position(x = -1.0f, y = 1.0f, z = 0.0f)` = left | top aligned -     ... |
