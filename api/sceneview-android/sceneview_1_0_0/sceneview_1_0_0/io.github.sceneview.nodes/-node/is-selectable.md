//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.nodes](../index.md)/[Node](index.md)/[isSelectable](is-selectable.md)

# isSelectable

[androidJvm]\
var [isSelectable](is-selectable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false

The node can be selected when a touch event happened

If a not selectable child [RenderableNode](../-renderable-node/index.md) is touched, we check the parent hierarchy to find the closest selectable parent. In this case, the first selectable parent will be the one to have its [isSelected](is-selected.md) value to `true`.