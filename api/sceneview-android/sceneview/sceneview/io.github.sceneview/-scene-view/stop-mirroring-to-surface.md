//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[stopMirroringToSurface](stop-mirroring-to-surface.md)

# stopMirroringToSurface

[androidJvm]\
fun [stopMirroringToSurface](stop-mirroring-to-surface.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html))

When capturing is complete, call this method to stop mirroring the SceneView to the specified [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). If this is not called, the additional performance cost will remain.

The application is responsible for calling [Surface.release](https://developer.android.com/reference/kotlin/android/view/Surface.html#release) on the Surface when done.
