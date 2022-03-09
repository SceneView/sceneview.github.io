//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Renderable](index.md)/[getFinalModelMatrix](get-final-model-matrix.md)

# getFinalModelMatrix

[androidJvm]\
open fun [getFinalModelMatrix](get-final-model-matrix.md)(originalMatrix: [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)

Gets the final model matrix to use for rendering this [Renderable](index.md) based on the matrix passed in. Default implementation simply passes through the original matrix. WARNING: Do not modify the originalMatrix! If the final matrix isn't the same as the original matrix, then a new instance must be returned.
