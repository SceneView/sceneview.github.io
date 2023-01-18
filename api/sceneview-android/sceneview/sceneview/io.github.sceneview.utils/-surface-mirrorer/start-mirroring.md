//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[SurfaceMirrorer](index.md)/[startMirroring](start-mirroring.md)

# startMirroring

[androidJvm]\
fun [startMirroring](start-mirroring.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = sceneView.width, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = sceneView.height)

##  Mirror the rendering to a surface

This can be used to video record the actual SceneView rendering.

To capture the contents of this view, designate a [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html) onto which this SceneView should be mirrored. Use [android.media.MediaRecorder.getSurface](https://developer.android.com/reference/kotlin/android/media/MediaRecorder.html#getsurface), [android.media.MediaCodec.createInputSurface](https://developer.android.com/reference/kotlin/android/media/MediaCodec.html#createinputsurface) or [android.media.MediaCodec.createPersistentInputSurface](https://developer.android.com/reference/kotlin/android/media/MediaCodec.html#createpersistentinputsurface) to obtain the input surface for recording. This will incur a rendering performance cost and should only be set when capturing this view. To stop the additional rendering, call stopMirroringToSurface.

## Parameters

androidJvm

| | |
|---|---|
| surface | the Surface onto which the rendered scene should be mirrored. |
| left | the left edge of the rectangle into which the view should be mirrored on surface. |
| bottom | the bottom edge of the rectangle into which the view should be mirrored on surface. |
| width | the width of the rectangle into which the SceneView should be mirrored on surface. |
| height | the height of the rectangle into which the SceneView should be mirrored on surface. |
