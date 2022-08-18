//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Renderable](index.md)/[prepareForDraw](prepare-for-draw.md)

# prepareForDraw

[androidJvm]\
open fun [prepareForDraw](prepare-for-draw.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md))

Optionally override in subclasses for work that must be done each frame for specific types of Renderables. For example, ViewRenderable uses this to prevent the renderable from being visible until the view has been successfully drawn to an external texture, and initializing material parameters.
