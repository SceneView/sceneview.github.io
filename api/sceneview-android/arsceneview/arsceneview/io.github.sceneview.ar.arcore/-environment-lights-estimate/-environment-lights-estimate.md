//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[EnvironmentLightsEstimate](index.md)/[EnvironmentLightsEstimate](-environment-lights-estimate.md)

# EnvironmentLightsEstimate

[androidJvm]\
fun [EnvironmentLightsEstimate](-environment-lights-estimate.md)(timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), environment: [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md), mainLight: [Light](../../../../sceneview/io.github.sceneview.light/-light/index.md)? = null)

## Parameters

androidJvm

| | |
|---|---|
| environment |  The retrieved environment<br>Environmental HDR mode uses machine learning to analyze the camera images in real time and synthesize environmental lighting to support realistic rendering of virtual objects.<br>-     Ambient spherical harmonics. Represents the remaining ambient light energy in the scene -     An HDR cubemap is used to render reflections in shiny metallic objects. |
| mainLight |  Main directionnal light (Usually the sun)<br>The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects. |
