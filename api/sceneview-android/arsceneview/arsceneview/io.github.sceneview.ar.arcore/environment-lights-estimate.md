//[arsceneview](../../index.md)/[io.github.sceneview.ar.arcore](index.md)/[environmentLightsEstimate](environment-lights-estimate.md)

# environmentLightsEstimate

[androidJvm]\
fun [ArFrame](-ar-frame/index.md).[environmentLightsEstimate](environment-lights-estimate.md)(config: [LightEstimationMode](-light-estimation-mode/index.md), previousEstimate: [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)?, baseEnvironment: [Environment](../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md)?, baseLight: [Light](../../../sceneview/io.github.sceneview.light/-light/index.md)?, cameraExposureFactor: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)?

###  The frame estimated environment

ARCore will estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

A key part for creating realistic AR experiences is getting the lighting right. When a virtual object is missing a shadow or has a shiny material that doesn't reflect the surrounding space, users can sense that the object doesn't quite fit, even if they can't explain why. This is because humans subconsciously perceive cues regarding how objects are lit in their environment. The Lighting Estimation API analyzes given images for such cues, providing detailed information about the lighting in a scene. You can then use this information when rendering virtual objects to light them under the same conditions as the scene they're placed in, keeping users grounded and engaged.

## Parameters

androidJvm

| | |
|---|---|
| cameraExposureFactor | ARCore's light estimation uses unit-less (relative) values while Filament uses a physically based camera model with lux or lumen values. In order to keep the "standard" Filament behavior we scale AR Core values. Infos: https://github.com/ThomasGorisse/SceneformMaintained/pull/156#issuecomment-911873565 |
