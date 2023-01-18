//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.view](index.md)/[worldToViewport](world-to-viewport.md)

# worldToViewport

[androidJvm]\
fun [FilamentView](index.md#45027628%2FClasslikes%2F-602047187).[worldToViewport](world-to-viewport.md)(worldPosition: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)

Get a screen space position from a world space position

#### Return

Viewport space position in Filament screen coordinates: BottomLeft = (0, 0), TopRight = (viewport Width, viewport Height).

The device coordinate space is unaffected by the orientation of the device

## See also

androidJvm

| | |
|---|---|
| [viewportToWorld](viewport-to-world.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| worldPosition | The world position to convert |
