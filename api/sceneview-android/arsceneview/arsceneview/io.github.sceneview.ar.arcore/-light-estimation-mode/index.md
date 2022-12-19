//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimationMode](index.md)

# LightEstimationMode

[androidJvm]\
enum [LightEstimationMode](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[LightEstimationMode](index.md)&gt; 

###  ARCore light estimation configuration

ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

Light bounces off of surfaces differently depending on whether the surface has specular (highly reflective) or diffuse (not reflective) properties. For example, a metallic ball will be highly specular and reflect its environment, while another ball painted a dull matte gray will be diffuse. Most real-world objects have a combination of these properties — think of a scuffed-up bowling ball or a well-used credit card.

Reflective surfaces also pick up colors from the ambient environment. The coloring of an object can be directly affected by the coloring of its environment. For example, a white ball in a blue room will take on a bluish hue.

The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects.

## Entries

| | |
|---|---|
| [ENVIRONMENTAL_HDR](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r/index.md) | [androidJvm]<br>[ENVIRONMENTAL_HDR](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r/index.md)<br>Use this mode if you want your objects to be more like if they where real. |
| [ENVIRONMENTAL_HDR_FAKE_REFLECTIONS](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-f-a-k-e_-r-e-f-l-e-c-t-i-o-n-s/index.md) | [androidJvm]<br>[ENVIRONMENTAL_HDR_FAKE_REFLECTIONS](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-f-a-k-e_-r-e-f-l-e-c-t-i-o-n-s/index.md)<br>The environmentalHdrReflections will be false and the SceneView default static environment will be rendered on reflective objects |
| [ENVIRONMENTAL_HDR_NO_REFLECTIONS](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-n-o_-r-e-f-l-e-c-t-i-o-n-s/index.md) | [androidJvm]<br>[ENVIRONMENTAL_HDR_NO_REFLECTIONS](-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-n-o_-r-e-f-l-e-c-t-i-o-n-s/index.md)<br>The environmentalHdrReflections will be false and the SceneView default static environment will also not be used (defaultEnvironmentReflections is false) |
| [AMBIENT_INTENSITY](-a-m-b-i-e-n-t_-i-n-t-e-n-s-i-t-y/index.md) | [androidJvm]<br>[AMBIENT_INTENSITY](-a-m-b-i-e-n-t_-i-n-t-e-n-s-i-t-y/index.md)<br>Use this mode if you only want to apply ARCore lights colors and intensity |
| [DISABLED](-d-i-s-a-b-l-e-d/index.md) | [androidJvm]<br>[DISABLED](-d-i-s-a-b-l-e-d/index.md)<br>The reflected environment will the default one or the one defined by [SceneView.environment](../../io.github.sceneview.ar/-ar-scene-view/index.md#-769674583%2FProperties%2F-58641720) |

## Properties

| Name | Summary |
|---|---|
| [name](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-372974862%2FProperties%2F-58641720) | [androidJvm]<br>val [name](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-372974862%2FProperties%2F-58641720): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-739389684%2FProperties%2F-58641720) | [androidJvm]<br>val [ordinal](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-t-o-p_-m-o-s-t/index.md#-739389684%2FProperties%2F-58641720): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [precision](precision.md) | [androidJvm]<br>val [precision](precision.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f |
