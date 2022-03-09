//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[TransformationSystem](index.md)/[selectNode](select-node.md)

# selectNode

[androidJvm]\
open fun [selectNode](select-node.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)node: [BaseTransformableNode](../-base-transformable-node/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Sets a [BaseTransformableNode](../-base-transformable-node/index.md) as the selected node if there is no currently selected node or if the currently selected node is not actively being transformed. If null, then deselects the currently selected node if the node is not transforming.

#### Return

true if the node was successfully selected

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.ux.BaseTransformableNode](../-base-transformable-node/is-transforming.md) |  |
