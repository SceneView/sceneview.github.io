//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[loadModelAsync](load-model-async.md)

# loadModelAsync

[androidJvm]\
fun [loadModelAsync](load-model-async.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html)? = null, autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, autoScale: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: (instance: [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)

###  Loads a monolithic binary glTF and add it to the Node

## Parameters

androidJvm

| | |
|---|---|
| glbFileLocation | the glb file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
| coroutineScope | your Activity or Fragment coroutine scope if you want to preload the 3D model before the node is attached to the [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| autoAnimate | Plays the animations automatically if the model has one |
| autoScale | Scale the model to fit a unit cube |
| centerOrigin | Center the model origin to this unit cube position<br>-     null = Keep the original model center point -     (0, -1, 0) = Center the model horizontally and vertically -     (0, -1, 0) = center horizontal | bottom aligned -     (-1, 1, 0) = left | top aligned -     ... |
