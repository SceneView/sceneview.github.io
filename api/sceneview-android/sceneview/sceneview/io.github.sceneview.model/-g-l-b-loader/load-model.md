//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLBLoader](index.md)/[loadModel](load-model.md)

# loadModel

[androidJvm]\
suspend fun [loadModel](load-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ModelRenderable](../../com.google.ar.sceneform.rendering/-model-renderable/index.md)?

###  Utility for loading a glTF 3D model

## Parameters

androidJvm

| | |
|---|---|
| glbFileLocation | the glb file location:<br>-     A relative asset file location *models/mymodel.glb* -     An android resource from the res folder *context.getResourceUri(R.raw.mymodel)* -     A File path *Uri.fromFile(myModelFile).path* -     An http or https url *https://mydomain.com/mymodel.glb* |
