//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[indirectLight](indirect-light.md)

# indirectLight

[androidJvm]\
var [indirectLight](indirect-light.md): IndirectLight?

IndirectLight is used to simulate environment lighting

Environment lighting has a two components:

- 
   irradiance
- 
   reflections (specular component)

Indirect light are usually captured as high-resolution HDR equirectangular images and processed by the cmgen tool to generate the data needed.

You can also process an hdr at runtime but this is more consuming

Currently IndirectLight is intended to be used for &quot;distant probes&quot;, that is, to represent global illumination from a distant (i.e. at infinity) environment, such as the sky or distant mountains. Only a single IndirectLight can be used in a Scene. This limitation will be lifted in the future.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.IndirectLight |  |
| com.google.android.filament.Scene |  |
| [KTX1Loader.loadIndirectLight](../../io.github.sceneview.loaders/load-indirect-light.md) |  |
| [HDRLoader.loadIndirectLight](../../io.github.sceneview.loaders/load-indirect-light.md) |  |
