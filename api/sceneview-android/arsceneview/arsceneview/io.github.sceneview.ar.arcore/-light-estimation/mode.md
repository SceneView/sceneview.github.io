//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimation](index.md)/[mode](mode.md)

# mode

[androidJvm]\
var [mode](mode.md): [LightEstimationMode](../-light-estimation-mode/index.md)

###  ARCore light estimation configuration

ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

Light bounces off of surfaces differently depending on whether the surface has specular (highly reflective) or diffuse (not reflective) properties. For example, a metallic ball will be highly specular and reflect its environment, while another ball painted a dull matte gray will be diffuse. Most real-world objects have a combination of these properties — think of a scuffed-up bowling ball or a well-used credit card.

Reflective surfaces also pick up colors from the ambient environment. The coloring of an object can be directly affected by the coloring of its environment. For example, a white ball in a blue room will take on a bluish hue.

The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.arcore.LightEstimationMode.ENVIRONMENTAL_HDR](../-light-estimation-mode/-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r/index.md) |  |
| [io.github.sceneview.ar.arcore.LightEstimationMode.ENVIRONMENTAL_HDR_NO_REFLECTIONS](../-light-estimation-mode/-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-n-o_-r-e-f-l-e-c-t-i-o-n-s/index.md) |  |
| [io.github.sceneview.ar.arcore.LightEstimationMode.ENVIRONMENTAL_HDR_FAKE_REFLECTIONS](../-light-estimation-mode/-e-n-v-i-r-o-n-m-e-n-t-a-l_-h-d-r_-f-a-k-e_-r-e-f-l-e-c-t-i-o-n-s/index.md) |  |
| [io.github.sceneview.ar.arcore.LightEstimationMode.AMBIENT_INTENSITY](../-light-estimation-mode/-a-m-b-i-e-n-t_-i-n-t-e-n-s-i-t-y/index.md) |  |
| [io.github.sceneview.ar.arcore.LightEstimationMode.DISABLED](../-light-estimation-mode/-d-i-s-a-b-l-e-d/index.md) |  |
