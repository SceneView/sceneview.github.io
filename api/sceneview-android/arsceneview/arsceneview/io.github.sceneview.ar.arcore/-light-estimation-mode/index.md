//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimationMode](index.md)

# LightEstimationMode

[androidJvm]\
data class [LightEstimationMode](index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(sessionConfigMode: Config.LightEstimationMode, environmentalHdrReflections: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environmentalHdrSphericalHarmonics: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environmentalHdrSpecularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environmentalHdrMainLightDirection: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environmentalHdrMainLightIntensity: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

###  ARCore light estimation configuration

ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

Light bounces off of surfaces differently depending on whether the surface has specular (highly reflective) or diffuse (not reflective) properties. For example, a metallic ball will be highly specular and reflect its environment, while another ball painted a dull matte gray will be diffuse. Most real-world objects have a combination of these properties — think of a scuffed-up bowling ball or a well-used credit card.

Reflective surfaces also pick up colors from the ambient environment. The coloring of an object can be directly affected by the coloring of its environment. For example, a white ball in a blue room will take on a bluish hue.

The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects.

## Parameters

androidJvm

| | |
|---|---|
| sessionConfigMode |  The behavior of the lighting estimation subsystem.<br>These modes consist of separate APIs that allow for granular and realistic lighting estimation for directional lighting, shadows, specular highlights, and reflections. |
| environmentalHdrReflections |  Enable reflection cubemap<br>-     true if the AR Core reflection cubemap should be used -     false for using the default/static/fake environment reflections<br>Use the HDR cubemap to render realistic reflections on virtual objects with medium to high glossiness, such as shiny metallic surfaces. The cubemap also affects the shading and appearance of objects. For example, the material of a specular object surrounded by a blue environment will reflect blue hues. Calculating the HDR cubemap requires a small amount of additional CPU computation. |
| environmentalHdrSphericalHarmonics |  Ambient spherical harmonics<br>In addition to the light energy in the main directional light, ARCore provides spherical harmonics, representing the overall ambient light coming in from all directions in the scene. Add subtle cues that bring out the definition of virtual objects. |
| environmentalHdrSpecularFilter |  SpecularFilter applies a filter based on the BRDF<br>used for lighting<br>Specular highlights are the shiny bits of surfaces that reflect a light source directly. Highlights on an object change relative to the position of a viewer in a scene.<br>true = Reduce the amount of reflectivity a surface has. It is a key component in determining the brightness of specular highlights, along with shininess to determine the size of the highlights. |
| environmentalHdrMainLightDirection |  Move the directional light<br>When the main light source or a lit object is in motion, the specular highlight on the object adjusts its position in real time relative to the light source.<br>Directional shadows also adjust their length and direction relative to the position of the main light source, just as they do in the real world. |
| environmentalHdrMainLightIntensity |  Modulate the main directional light (sun) intensity |

## Constructors

| | |
|---|---|
| [LightEstimationMode](-light-estimation-mode.md) | [androidJvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [LightEstimationMode](-light-estimation-mode.md)(sessionConfigMode: Config.LightEstimationMode = Config.LightEstimationMode.ENVIRONMENTAL_HDR, environmentalHdrReflections: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, environmentalHdrSphericalHarmonics: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, environmentalHdrSpecularFilter: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, environmentalHdrMainLightDirection: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, environmentalHdrMainLightIntensity: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [environmentalHdrMainLightDirection](environmental-hdr-main-light-direction.md) | [androidJvm]<br>val [environmentalHdrMainLightDirection](environmental-hdr-main-light-direction.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [environmentalHdrMainLightIntensity](environmental-hdr-main-light-intensity.md) | [androidJvm]<br>val [environmentalHdrMainLightIntensity](environmental-hdr-main-light-intensity.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [environmentalHdrReflections](environmental-hdr-reflections.md) | [androidJvm]<br>val [environmentalHdrReflections](environmental-hdr-reflections.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md) | [androidJvm]<br>val [environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [environmentalHdrSphericalHarmonics](environmental-hdr-spherical-harmonics.md) | [androidJvm]<br>val [environmentalHdrSphericalHarmonics](environmental-hdr-spherical-harmonics.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [sessionConfigMode](session-config-mode.md) | [androidJvm]<br>val [sessionConfigMode](session-config-mode.md): Config.LightEstimationMode |
