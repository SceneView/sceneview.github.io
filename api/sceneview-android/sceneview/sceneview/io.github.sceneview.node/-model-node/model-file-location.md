//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[modelFileLocation](model-file-location.md)

# modelFileLocation

[androidJvm]\
var [modelFileLocation](model-file-location.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null

###  Loads a monolithic binary glTF and add it to the Node

The glb file location:

- 
   A relative asset file location *models/mymodel.glb*
- 
   An android resource from the res folder *context.getResourceUri(R.raw.mymodel)*
- 
   A File path *Uri.fromFile(myModelFile).path*
- 
   An http or https url *https://mydomain.com/mymodel.glb*

The load is done instantly if the node is already attached to the SceneView. Else, it will be loaded when SceneView is attached because it needs a [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html) and [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) to load

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.node.ModelNode](load-model.md) |  |
