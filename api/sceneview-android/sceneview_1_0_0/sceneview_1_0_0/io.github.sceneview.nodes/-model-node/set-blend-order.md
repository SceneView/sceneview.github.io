//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.nodes](../index.md)/[ModelNode](index.md)/[setBlendOrder](set-blend-order.md)

# setBlendOrder

[androidJvm]\
fun [setBlendOrder](set-blend-order.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 65535)blendOrder: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Changes the drawing order for blended primitives

The drawing order is either global or local (default) to this Renderable. In either case, the Renderable priority takes precedence.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.components.RenderableComponent](../../io.github.sceneview.components/-renderable-component/set-blend-order.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| blendOrder | draw order number (0 by default). Only the lowest 15 bits are used |
