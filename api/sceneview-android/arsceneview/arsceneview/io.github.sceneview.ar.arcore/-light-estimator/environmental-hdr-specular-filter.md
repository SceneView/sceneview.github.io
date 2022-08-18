//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimator](index.md)/[environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md)

# environmentalHdrSpecularFilter

[androidJvm]\
var [environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false

###  SpecularFilter applies a filter based on the BRDF used for lighting

Specular highlights are the shiny bits of surfaces that reflect a light source directly. Highlights on an object change relative to the position of a viewer in a scene.

true = Reduce the amount of reflectivity a surface has. It is a key component in determining the brightness of specular highlights, along with shininess to determine the size of the highlights.
