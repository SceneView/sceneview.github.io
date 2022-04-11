//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimation](index.md)/[environmentalHdrReflections](environmental-hdr-reflections.md)

# environmentalHdrReflections

[androidJvm]\
var [environmentalHdrReflections](environmental-hdr-reflections.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true

###  Enable reflection cubemap

- 
   true if the AR Core reflection cubemap should be used
- 
   false for using the default/static/fake environment reflections

Use the HDR cubemap to render realistic reflections on virtual objects with medium to high glossiness, such as shiny metallic surfaces. The cubemap also affects the shading and appearance of objects. For example, the material of a specular object surrounded by a blue environment will reflect blue hues. Calculating the HDR cubemap requires a small amount of additional CPU computation.
