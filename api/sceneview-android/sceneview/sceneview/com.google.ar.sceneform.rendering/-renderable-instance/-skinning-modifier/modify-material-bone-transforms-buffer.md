//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[RenderableInstance](../index.md)/[SkinningModifier](index.md)/[modifyMaterialBoneTransformsBuffer](modify-material-bone-transforms-buffer.md)

# modifyMaterialBoneTransformsBuffer

[androidJvm]\
abstract fun [modifyMaterialBoneTransformsBuffer](modify-material-bone-transforms-buffer.md)(originalBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)

Takes the original boneTransforms and output new boneTransforms used to render the mesh.

## Parameters

androidJvm

| | |
|---|---|
| originalBuffer | contains the bone transforms from the current animation state of the skeleton, buffer is read only |
