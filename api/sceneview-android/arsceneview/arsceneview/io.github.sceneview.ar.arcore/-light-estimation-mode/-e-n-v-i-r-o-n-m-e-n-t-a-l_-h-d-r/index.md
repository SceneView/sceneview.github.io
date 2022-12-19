//[arsceneview](../../../../index.md)/[io.github.sceneview.ar.arcore](../../index.md)/[LightEstimationMode](../index.md)/[ENVIRONMENTAL_HDR](index.md)

# ENVIRONMENTAL_HDR

[androidJvm]\
[ENVIRONMENTAL_HDR](index.md)

###  Environmental HDR mode estimated environment

Use this mode if you want your objects to be more like if they where real.

Lighting estimation is enabled, generating inferred Environmental HDR lighting estimation in linear color space.

This mode is incompatible with the front-facing (selfie) camera. If set on a Session created for the front-facing camera, the call to configure will fail. These modes consist of separate APIs that allow for granular and realistic lighting estimation for directional lighting, shadows, specular highlights, and reflections.

Environmental HDR mode uses machine learning to analyze the camera images in real time and synthesize environmental lighting to support realistic rendering of virtual objects.

This lighting estimation mode provides:

1. 
   Main directional light. Represents the main light source. Can be used to cast shadows 2.Ambient spherical harmonics. Represents the remaining ambient light energy in the scene 3.An HDR cubemap. Can be used to render reflections in shiny metallic objects

Specular highlights are the shiny bits of surfaces that reflect a light source directly. More highlights on an object change relative to the position of a viewer in a scene. With this mode, the reflections will come from ARCore.

The environmentalHdrReflections will be true.

The reflected environment will the one given by ARCore

## Properties

| Name | Summary |
|---|---|
| [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-372974862%2FProperties%2F-58641720) | [androidJvm]<br>val [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-372974862%2FProperties%2F-58641720): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-739389684%2FProperties%2F-58641720) | [androidJvm]<br>val [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-739389684%2FProperties%2F-58641720): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [precision](../precision.md) | [androidJvm]<br>val [precision](../precision.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f |
