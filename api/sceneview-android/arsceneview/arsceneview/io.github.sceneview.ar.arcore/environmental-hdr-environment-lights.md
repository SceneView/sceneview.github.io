//[arsceneview](../../index.md)/[io.github.sceneview.ar.arcore](index.md)/[environmentalHdrEnvironmentLights](environmental-hdr-environment-lights.md)

# environmentalHdrEnvironmentLights

[androidJvm]\
fun LightEstimate.[environmentalHdrEnvironmentLights](environmental-hdr-environment-lights.md)(previousEstimate: [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)?, baseEnvironment: [Environment](../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md)?, baseLight: [Light](../../../sceneview/io.github.sceneview.light/-light/index.md)?, cameraExposureFactor: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), withReflections: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), withSphericalHarmonics: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), withSpecularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), withDirection: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, withIntensity: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true): [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)

###  Environmental HDR mode estimated environment

Lighting estimation is enabled, generating inferred Environmental HDR lighting estimation in linear color space.

This mode is incompatible with the front-facing (selfie) camera. If set on a Session created for the front-facing camera, the call to configure will fail. These modes consist of separate APIs that allow for granular and realistic lighting estimation for directional lighting, shadows, specular highlights, and reflections.

Environmental HDR mode uses machine learning to analyze the camera images in real time and synthesize environmental lighting to support realistic rendering of virtual objects.

This lighting estimation mode provides:

1. 
   Main directional light. Represents the main light source. Can be used to cast shadows. 2.Ambient spherical harmonics. Represents the remaining ambient light energy in the scene. 3.An HDR cubemap. Can be used to render reflections in shiny metallic objects.

## Parameters

androidJvm

| | |
|---|---|
| cameraExposureFactor | ARCore's light estimation uses unit-less (relative) values while Filament uses a physically based camera model with lux or lumen values. In order to keep the "standard" Filament behavior we scale AR Core values. Infos: https://github.com/ThomasGorisse/SceneformMaintained/pull/156#issuecomment-911873565 |
