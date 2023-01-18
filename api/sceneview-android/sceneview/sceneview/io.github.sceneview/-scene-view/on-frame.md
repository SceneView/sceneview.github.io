//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[onFrame](on-frame.md)

# onFrame

[androidJvm]\
var [onFrame](on-frame.md): (frameTime: [FrameTime](../../io.github.sceneview.utils/-frame-time/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when an frame is processed

Registers a callback to be invoked when a valid Frame is processing.

The callback to be invoked once per frame **immediately before the scene is updated**.

The callback will only be invoked if the Frame is considered as valid.
