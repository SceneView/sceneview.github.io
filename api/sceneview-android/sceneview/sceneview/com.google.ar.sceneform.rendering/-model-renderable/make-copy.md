//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ModelRenderable](index.md)/[makeCopy](make-copy.md)

# makeCopy

[androidJvm]\
open fun [makeCopy](make-copy.md)(): [ModelRenderable](index.md)

Creates a new instance of this ModelRenderable. 

The new renderable will have unique copy of all mutable state. All materials referenced by the ModelRenderable will also be instanced. Immutable data will be shared between the instances.
