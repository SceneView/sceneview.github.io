//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ViewRenderable](index.md)/[makeCopy](make-copy.md)

# makeCopy

[androidJvm]\
open fun [makeCopy](make-copy.md)(): [ViewRenderable](index.md)

Creates a new instance of this ViewRenderable. 

The new renderable will have unique copy of all mutable state. All materials referenced by the ViewRenderable will also be instanced. Immutable data will be shared between the instances. The new ViewRenderable will reference the same getFilamentEngine View as the original ViewRenderable.
