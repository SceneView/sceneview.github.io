//[sceneview](../../index.md)/[io.github.sceneview.environment](index.md)/[createTexture](create-texture.md)

# createTexture

[androidJvm]\
fun HDRLoader.[createTexture](create-texture.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), options: HDRLoader.Options = HDRLoader.Options(), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): Texture?

###  Consumes the content of an HDR file and produces a Texture object.

#### Return

The resulting Filament texture, or null on failure.

## Parameters

androidJvm

| | |
|---|---|
| buffer | The content of the HDR File. |
| options | Loader options. |
