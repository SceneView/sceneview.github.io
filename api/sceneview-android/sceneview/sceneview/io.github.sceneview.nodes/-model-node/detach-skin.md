//[sceneview](../../../index.md)/[io.github.sceneview.nodes](../index.md)/[ModelNode](index.md)/[detachSkin](detach-skin.md)

# detachSkin

[androidJvm]\
fun [detachSkin](detach-skin.md)(target: [Node](../-node/index.md), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)skinIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0)

Attaches the given skin to the given node, which must have an associated mesh with BONE_INDICES and BONE_WEIGHTS attributes.

This is a no-op if the given skin index or target is invalid.
