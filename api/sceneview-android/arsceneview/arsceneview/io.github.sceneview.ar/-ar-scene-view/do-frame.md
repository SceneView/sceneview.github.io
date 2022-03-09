//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[doFrame](do-frame.md)

# doFrame

[androidJvm]\
open override fun [doFrame](do-frame.md)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md))

Before the render call occurs, update the ARCore session to grab the latest frame and update listeners.

The super.onFrame() is called if the session updated successfully and a new frame was obtained. Update the scene before rendering.
