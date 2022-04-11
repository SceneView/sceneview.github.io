//[arsceneview](../../../../index.md)/[io.github.sceneview.ar.arcore](../../index.md)/[LightEstimationMode](../index.md)/[AMBIENT_INTENSITY](index.md)

# AMBIENT_INTENSITY

[androidJvm]\
[AMBIENT_INTENSITY](index.md)()

###  Ambient Intensity mode estimated environment

Use this mode if you only want to apply ARCore lights colors and intensity

Lighting estimation is enabled, generating a single-value intensity estimate and three (R, G, B) color correction values

Ambient Intensity mode determines the average pixel intensity and the color correction scalars for a given image. It's a coarse setting designed for use cases where precise lighting is not critical, such as objects that have baked-in lighting.

The reflected environment will the default one or the one defined by [SceneView.environment](../../../io.github.sceneview.ar/-ar-scene-view/index.md#-769674583%2FProperties%2F-58641720)

## Properties

| Name | Summary |
|---|---|
| [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-372974862%2FProperties%2F-58641720) | [androidJvm]<br>val [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-372974862%2FProperties%2F-58641720): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-739389684%2FProperties%2F-58641720) | [androidJvm]<br>val [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-739389684%2FProperties%2F-58641720): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [precision](../precision.md) | [androidJvm]<br>val [precision](../precision.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f |
