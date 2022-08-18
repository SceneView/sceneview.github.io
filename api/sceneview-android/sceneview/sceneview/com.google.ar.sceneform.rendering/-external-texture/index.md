//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ExternalTexture](index.md)

# ExternalTexture

[androidJvm]\
open class [ExternalTexture](index.md)

Creates an Android [SurfaceTexture](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html) and [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html) that can be displayed by Sceneform. Useful for displaying video, or anything else that can be drawn to a [SurfaceTexture](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html). 

The getFilamentEngine OpenGL ES texture is automatically created by Sceneform. Also, [updateTexImage](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html#updateteximage) is automatically called and should not be called manually. 

Call [setExternalTexture](../-material/set-external-texture.md) to use an ExternalTexture. The material parameter MUST be of type 'samplerExternal'.

## Constructors

| | |
|---|---|
| [ExternalTexture](-external-texture.md) | [androidJvm]<br>open fun [ExternalTexture](-external-texture.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html))<br>Creates an ExternalTexture with a new Android [SurfaceTexture](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html) and [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [filamentStream](filament-stream.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [filamentStream](filament-stream.md): Stream |
| [filamentTexture](filament-texture.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [filamentTexture](filament-texture.md): Texture |
| [surface](surface.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private val [surface](surface.md): [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html) |
| [surfaceTexture](surface-texture.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private val [surfaceTexture](surface-texture.md): [SurfaceTexture](https://developer.android.com/reference/kotlin/android/graphics/SurfaceTexture.html) |
