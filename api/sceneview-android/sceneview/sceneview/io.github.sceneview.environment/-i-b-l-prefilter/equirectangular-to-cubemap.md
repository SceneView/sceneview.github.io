//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[IBLPrefilter](index.md)/[equirectangularToCubemap](equirectangular-to-cubemap.md)

# equirectangularToCubemap

[androidJvm]\
fun [equirectangularToCubemap](equirectangular-to-cubemap.md)(equirect: Texture): Texture

###  Converts an equirectangular image to a cubemap.

#### Return

the cubemap texture

## See also

androidJvm

| | |
|---|---|
| EquirectangularToCubemap |  |

## Parameters

androidJvm

| | |
|---|---|
| equirect | Texture to convert to a cubemap.<br>-     Can't be null. -     Must be a 2d texture -     Must have equirectangular geometry, that is width == 2*height. -     Must be allocated with all mip levels. -     Must be SAMPLEABLE |
