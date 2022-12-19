//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[RenderableComponent](index.md)/[setBlendOrder](set-blend-order.md)

# setBlendOrder

[androidJvm]\
open fun [setBlendOrder](set-blend-order.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 65535)blendOrder: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Changes the drawing order for blended primitives.

The drawing order is either global or local (default) to this Renderable. In either case, the Renderable priority takes precedence.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.components.RenderableComponent](set-blend-order-at.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| blendOrder | draw order number (0 by default). Only the lowest 15 bits are used. |
