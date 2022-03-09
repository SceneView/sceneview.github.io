//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[onArFrame](on-ar-frame.md)

# onArFrame

[androidJvm]\
var [onArFrame](on-ar-frame.md): (arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when an ARCore frame is processed

Registers a callback to be invoked when a valid ARCore Frame is processing.

The callback to be invoked once per frame **immediately before the scene is updated**.

The callback will only be invoked if the Frame is considered as valid.
