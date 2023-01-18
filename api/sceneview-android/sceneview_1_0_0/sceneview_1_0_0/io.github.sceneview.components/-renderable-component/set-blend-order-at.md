//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.components](../index.md)/[RenderableComponent](index.md)/[setBlendOrderAt](set-blend-order-at.md)

# setBlendOrderAt

[androidJvm]\
open fun [setBlendOrderAt](set-blend-order-at.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)primitiveIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 65535)blendOrder: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Changes the drawing order for blended primitives. The drawing order is either global or local (default) to this Renderable.

In either case, the Renderable priority takes precedence.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.RenderableManager |  |

## Parameters

androidJvm

| | |
|---|---|
| primitiveIndex | the primitive of interest |
| blendOrder | draw order number (0 by default). Only the lowest 15 bits are used. |
