//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Renderable](index.md)/[makeCopy](make-copy.md)

# makeCopy

[androidJvm]\
abstract fun [makeCopy](make-copy.md)(): [Renderable](index.md)

Creates a new instance of this Renderable. 

The new renderable will have unique copy of all mutable state. All materials referenced by the Renderable will also be instanced. Immutable data will be shared between the instances.
