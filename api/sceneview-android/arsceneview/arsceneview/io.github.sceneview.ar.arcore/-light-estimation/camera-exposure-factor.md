//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimation](index.md)/[cameraExposureFactor](camera-exposure-factor.md)

# cameraExposureFactor

[androidJvm]\
var [cameraExposureFactor](camera-exposure-factor.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

###  Exposure normalization factor from the camera's EV100

ARCore's light estimation uses unit-less (relative) values while Filament uses a physically based camera model with lux or lumen values. In order to keep the "standard" Filament behavior we scale AR Core values. Infos: https://github.com/ThomasGorisse/SceneformMaintained/pull/156#issuecomment-911873565
