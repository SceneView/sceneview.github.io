//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[DepthTexture](index.md)

# DepthTexture

[androidJvm]\
open class [DepthTexture](index.md)```kotlin
    The DepthTexture class holds a special Texture to store
    information from a DepthImage or RawDepthImage to implement the occlusion of
    virtual objects behind real world objects.

```

## Constructors

| | |
|---|---|
| [DepthTexture](-depth-texture.md) | [androidJvm]<br>open fun [DepthTexture](-depth-texture.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>```kotlin      A call to this constructor creates a new Filament Texture which is      later used to feed in data from a DepthImage.<br>``` |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |
| [updateDepthTexture](update-depth-texture.md) | [androidJvm]<br>open fun [updateDepthTexture](update-depth-texture.md)(depthImage: [Image](https://developer.android.com/reference/kotlin/android/media/Image.html))<br>```kotlin     This is the most important function of this class.     The Filament Texture is updated based on the newest     DepthImage. To solve a problem with a to early     released DepthImage the ByteBuffer which holds all     necessary data is cloned. The cloned ByteBuffer is unaffected     of a released DepthImage and therefore produces not     a flickering result.<br>``` |

## Properties

| Name | Summary |
|---|---|
| [filamentTexture](filament-texture.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open val [filamentTexture](filament-texture.md): Texture |
