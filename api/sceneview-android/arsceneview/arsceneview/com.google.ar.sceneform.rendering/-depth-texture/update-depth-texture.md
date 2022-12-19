//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[DepthTexture](index.md)/[updateDepthTexture](update-depth-texture.md)

# updateDepthTexture

[androidJvm]\
open fun [updateDepthTexture](update-depth-texture.md)(depthImage: [Image](https://developer.android.com/reference/kotlin/android/media/Image.html))

```kotlin
    This is the most important function of this class.
    The Filament Texture is updated based on the newest
    DepthImage. To solve a problem with a to early
    released DepthImage the ByteBuffer which holds all
    necessary data is cloned. The cloned ByteBuffer is unaffected
    of a released DepthImage and therefore produces not
    a flickering result.

```

## Parameters

androidJvm

| | |
|---|---|
| depthImage | [Image](https://developer.android.com/reference/kotlin/android/media/Image.html) |
