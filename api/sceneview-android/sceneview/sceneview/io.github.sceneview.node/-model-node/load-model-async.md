//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[loadModelAsync](load-model-async.md)

# loadModelAsync

[androidJvm]\
fun [loadModelAsync](load-model-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null, glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, autoScale: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: (instance: [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null): [ModelNode](index.md)

###  Loads a monolithic binary glTF and add it to the Node

## Parameters

androidJvm

| | |
|---|---|
| lifecycle | Provide your lifecycle in order to load your model instantly and to destroy it (and its resources) when the lifecycle goes to destroy state. Otherwise the model loading is done when the parent [SceneView](../../io.github.sceneview/-scene-view/index.md) is attached because it needs a kotlinx.coroutines.CoroutineScope to load and resources will be destroyed when the [SceneView](../../io.github.sceneview/-scene-view/index.md) is. You are responsible of manually destroy this [Node](../-node/index.md) only if you don't provide lifecycle and the node is never attached to a [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| glbFileLocation | the glb file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
| coroutineScope | your Activity or Fragment coroutine scope if you want to preload the 3D model before the node is attached to the [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| autoAnimate | Plays the animations automatically if the model has one |
| autoScale | Scale the model to fit a unit cube |
| centerOrigin | Center the model origin to this unit cube position<br>-     null = Keep the original model center point -     Position(x = 0.0f, y = 0.0f, z = 0.0f) = Center the model horizontally and vertically -     Position(x = 0.0f, y = -1.0f, z = 0.0f) = center horizontal | bottom aligned -     Position(x = -1.0f, y = 1.0f, z = 0.0f) = left | top aligned -     ... |
