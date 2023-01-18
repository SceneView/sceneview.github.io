//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[RenderableInstance](index.md)/[setCulling](set-culling.md)

# setCulling

[androidJvm]\
open fun [setCulling](set-culling.md)(isCulling: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

### Changes whether or not frustum culling is on The view frustum is the region of space in the modeled world that may appear on the screen. Viewing-frustum culling is the process of removing objects that lie completely outside the viewing frustum from the rendering process. In other words, `true` = your model won't be visible/rendered when not any part of its bounding box is visible/inside the camera view. Rendering these object would be a waste of time since they are not directly visible. To make culling fast, it is usually done using bounding box surrounding the objects rather than the objects themselves. Instead of sending all information to your GPU, you will sort visible and invisible elements and render only visible elements. Thanks to this technique, you will earn GPU compute time. Do not confuse frustum culling with backface culling. The latter is controlled via the material true by default
