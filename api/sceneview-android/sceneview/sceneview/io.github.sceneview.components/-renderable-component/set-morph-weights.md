//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[RenderableComponent](index.md)/[setMorphWeights](set-morph-weights.md)

# setMorphWeights

[androidJvm]\
open fun [setMorphWeights](set-morph-weights.md)(weights: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = weights.size)

Updates the vertex morphing weights on a renderable, all zeroes by default.

The renderable must be built with morphing enabled. In legacy morphing mode, only the first 4 weights are considered.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.RenderableManager |  |
