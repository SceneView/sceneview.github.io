//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[startMirroringToSurface](start-mirroring-to-surface.md)

# startMirroringToSurface

[androidJvm]\
fun [startMirroringToSurface](start-mirroring-to-surface.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

To capture the contents of this view, designate a [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html) onto which this SceneView should be mirrored. Use [android.media.MediaRecorder.getSurface](https://developer.android.com/reference/kotlin/android/media/MediaRecorder.html#getsurface), [](https://developer.android.com/reference/kotlin/android/media/MediaCodec.html#createinputsurface) or [](https://developer.android.com/reference/kotlin/android/media/MediaCodec.html#createpersistentinputsurface) to obtain the input surface for recording. This will incur a rendering performance cost and should only be set when capturing this view. To stop the additional rendering, call stopMirroringToSurface.

## Parameters

androidJvm

| | |
|---|---|
| surface | the Surface onto which the rendered scene should be mirrored. |
| left | the left edge of the rectangle into which the view should be mirrored on surface. |
| bottom | the bottom edge of the rectangle into which the view should be mirrored on surface. |
| width | the width of the rectangle into which the SceneView should be mirrored on surface. |
| height | the height of the rectangle into which the SceneView should be mirrored on surface. |
