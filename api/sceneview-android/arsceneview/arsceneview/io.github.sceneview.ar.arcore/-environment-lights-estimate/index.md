//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[EnvironmentLightsEstimate](index.md)

# EnvironmentLightsEstimate

[androidJvm]\
class [EnvironmentLightsEstimate](index.md)(timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), environment: [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md), mainLight: [Light](../../../../sceneview/io.github.sceneview.light/-light/index.md)?)

###  Per frame AR light estimation values

## Parameters

androidJvm

| | |
|---|---|
| environment |  The retrieved environment<br>Environmental HDR mode uses machine learning to analyze the camera images in real time and synthesize environmental lighting to support realistic rendering of virtual objects.<br>-     Ambient spherical harmonics. Represents the remaining ambient light energy in the scene -     An HDR cubemap is used to render reflections in shiny metallic objects. |
| mainLight |  Main directionnal light (Usually the sun)<br>The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects. |

## Constructors

| | |
|---|---|
| [EnvironmentLightsEstimate](-environment-lights-estimate.md) | [androidJvm]<br>fun [EnvironmentLightsEstimate](-environment-lights-estimate.md)(timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), environment: [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md), mainLight: [Light](../../../../sceneview/io.github.sceneview.light/-light/index.md)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [environment](environment.md) | [androidJvm]<br>val [environment](environment.md): [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md) |
| [mainLight](main-light.md) | [androidJvm]<br>val [mainLight](main-light.md): [Light](../../../../sceneview/io.github.sceneview.light/-light/index.md)? = null |
| [timestamp](timestamp.md) | [androidJvm]<br>val [timestamp](timestamp.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
