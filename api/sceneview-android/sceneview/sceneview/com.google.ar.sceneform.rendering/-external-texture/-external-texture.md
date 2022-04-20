//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ExternalTexture](index.md)/[ExternalTexture](-external-texture.md)

# ExternalTexture

[androidJvm]\
open fun [ExternalTexture](-external-texture.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html))

Creates an ExternalTexture with a new Android [SurfaceTexture](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html) and [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html).

[androidJvm]\
open fun [ExternalTexture](-external-texture.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), textureId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Creates an ExternalTexture from an OpenGL ES textureId without a SurfaceTexture. For internal use only.
