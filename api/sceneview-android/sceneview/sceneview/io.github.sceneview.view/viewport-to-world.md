//[sceneview](../../index.md)/[io.github.sceneview.view](index.md)/[viewportToWorld](viewport-to-world.md)

# viewportToWorld

[androidJvm]\
fun [FilamentView](index.md#45027628%2FClasslikes%2F-1571379623).[viewportToWorld](viewport-to-world.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)

Get a world space position from a screen space position

#### Return

a new Position that represents the point in screen-space.

## See also

androidJvm

| | |
|---|---|
| [worldToViewport](world-to-viewport.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| x | (0..Viewport width) = (left..right) The X value is negative when the point is left of the viewport, between 0 and the width of the View.getViewport width when the point is within the viewport, and greater than the width when the point is to the right of the viewport. |
| y | (0..Viewport height) = (bottom..top) The Y value is negative when the point is below the viewport, between 0 and the height of the View.getViewport height when the point is within the viewport, and greater than the height when the point is above the viewport. |
| z | (0..1) (far..near) The Z value is used for the depth between 1 and 0 (1=near, 0=infinity). |
