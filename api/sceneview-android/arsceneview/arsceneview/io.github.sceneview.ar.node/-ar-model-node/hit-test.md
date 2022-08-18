//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[hitTest](hit-test.md)

# hitTest

[androidJvm]\
fun [hitTest](hit-test.md)(plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.planeEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.depthEnabled, instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.instantPlacementEnabled): HitResult?

###  Performs a ray cast to retrieve the ARCore info at this camera point

#### Return

the hitResult or null if no info is retrieved

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.arcore.ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| frame | the [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md) from where we take the HitResult By default the latest session frame if any exist |
| xPx | x view coordinate in pixels By default the [cameraPosition.x](hit-position.md) of this Node is used |
| yPx | y view coordinate in pixels By default the [cameraPosition.y](hit-position.md) of this Node is used |
