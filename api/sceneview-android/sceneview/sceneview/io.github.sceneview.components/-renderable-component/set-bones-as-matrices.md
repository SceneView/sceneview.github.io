//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[RenderableComponent](index.md)/[setBonesAsMatrices](set-bones-as-matrices.md)

# setBonesAsMatrices

[androidJvm]\
open fun [setBonesAsMatrices](set-bones-as-matrices.md)(matrices: [Buffer](https://docs.oracle.com/javase/8/docs/api/java/nio/Buffer.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 255)boneCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Sets the transforms associated with each bone of a Renderable.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.RenderableManager |  |

## Parameters

androidJvm

| | |
|---|---|
| matrices | A FloatBuffer containing boneCount 4x4 packed matrices (i.e. 16 floats each matrix and no gap between matrices) |
| boneCount | Number of bones to set |
| offset | Index of the first bone to set |
