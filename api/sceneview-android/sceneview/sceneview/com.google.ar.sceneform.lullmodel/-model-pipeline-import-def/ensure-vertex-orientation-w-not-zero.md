//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[ModelPipelineImportDef](index.md)/[ensureVertexOrientationWNotZero](ensure-vertex-orientation-w-not-zero.md)

# ensureVertexOrientationWNotZero

[androidJvm]\
open fun [ensureVertexOrientationWNotZero](ensure-vertex-orientation-w-not-zero.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Encodes a sign into the w value of the orientation quaternion such that >0 implies a right handed space, and <0 implies a left handed space. w==0 should never happen. This allows orientation components to be encoded in a
