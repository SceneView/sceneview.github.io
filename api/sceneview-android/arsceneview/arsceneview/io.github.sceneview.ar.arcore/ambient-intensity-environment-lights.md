//[arsceneview](../../index.md)/[io.github.sceneview.ar.arcore](index.md)/[ambientIntensityEnvironmentLights](ambient-intensity-environment-lights.md)

# ambientIntensityEnvironmentLights

[androidJvm]\
fun LightEstimate.[ambientIntensityEnvironmentLights](ambient-intensity-environment-lights.md)(previousEstimate: [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)?, baseEnvironment: [Environment](../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md)?, baseLight: [Light](../../../sceneview/io.github.sceneview.light/-light/index.md)?): [EnvironmentLightsEstimate](-environment-lights-estimate/index.md)

###  Ambient Intensity mode estimated environment

Lighting estimation is enabled, generating a single-value intensity estimate and three (R, G, B) color correction values

Ambient Intensity mode determines the average pixel intensity and the color correction scalars for a given image. It's a coarse setting designed for use cases where precise lighting is not critical, such as objects that have baked-in lighting.
