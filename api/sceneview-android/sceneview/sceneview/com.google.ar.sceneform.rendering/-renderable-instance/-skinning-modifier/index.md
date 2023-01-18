//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[RenderableInstance](../index.md)/[SkinningModifier](index.md)

# SkinningModifier

[androidJvm]\
interface [SkinningModifier](index.md)

Interface for modifying the bone transforms for this specific RenderableInstance. Used by SkeletonNode to make it possible to control a bone by moving a node.

## Functions

| Name | Summary |
|---|---|
| [isModifiedSinceLastRender](is-modified-since-last-render.md) | [androidJvm]<br>abstract fun [isModifiedSinceLastRender](is-modified-since-last-render.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [modifyMaterialBoneTransformsBuffer](modify-material-bone-transforms-buffer.md) | [androidJvm]<br>abstract fun [modifyMaterialBoneTransformsBuffer](modify-material-bone-transforms-buffer.md)(originalBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)<br>Takes the original boneTransforms and output new boneTransforms used to render the mesh. |
