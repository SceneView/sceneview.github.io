//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArSession](index.md)/[lightEstimationMode](light-estimation-mode.md)

# lightEstimationMode

[androidJvm]\
var [lightEstimationMode](light-estimation-mode.md): [LightEstimationMode](../-light-estimation-mode/index.md)

###  ARCore light estimation configuration

ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

Light bounces off of surfaces differently depending on whether the surface has specular (highly reflective) or diffuse (not reflective) properties. For example, a metallic ball will be highly specular and reflect its environment, while another ball painted a dull matte gray will be diffuse. Most real-world objects have a combination of these properties — think of a scuffed-up bowling ball or a well-used credit card.

Reflective surfaces also pick up colors from the ambient environment. The coloring of an object can be directly affected by the coloring of its environment. For example, a white ball in a blue room will take on a bluish hue.

The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects.

LightEstimationConfig.SPECTACULAR vs LightEstimationConfig.REALISTIC mostly differs on the reflections parts and you will mainly only see differences if your model has more metallic than roughness material values.

Adjust the based reference/factored lighting intensities and other values with:

- 
   [io.github.sceneview.ar.ArSceneView.mainLight](../../../../arsceneview/io.github.sceneview.ar/-ar-scene-view/main-light.md)
- 
   [io.github.sceneview.ar.ArSceneView.environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/indirect-light.md)

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.arcore.LightEstimationMode.Companion](../-light-estimation-mode/-companion/-d-i-s-a-b-l-e-d.md) |  |
