//[sceneview](../../index.md)/[io.github.sceneview.scene](index.md)/[setEnvironment](set-environment.md)

# setEnvironment

[androidJvm]\
fun Scene.[setEnvironment](set-environment.md)(environment: [Environment](../io.github.sceneview.environment/-environment/index.md)?)

###  Defines the lighting environment and the skybox of the scene

Environments are usually captured as high-resolution HDR equirectangular images and processed by the cmgen tool to generate the data needed by IndirectLight.

You can also process an hdr at runtime but this is more consuming.

- 
   Currently IndirectLight is intended to be used for "distant probes", that is, to represent global illumination from a distant (i.e. at infinity) environment, such as the sky or distant mountains. Only a single IndirectLight can be used in a Scene. This limitation will be lifted in the future.
- 
   When added to a Scene, the Skybox fills all untouched pixels.

#### Return

the created directional light

## See also

androidJvm

| | |
|---|---|
| KTXLoader.loadEnvironment |  |
| HDRLoader.loadEnvironment |  |
