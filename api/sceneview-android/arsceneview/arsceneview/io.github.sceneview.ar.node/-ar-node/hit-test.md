//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[hitTest](hit-test.md)

# hitTest

[androidJvm]\
fun [hitTest](hit-test.md)(frame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)? = arSession?.currentFrame, xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = placementMode.instantPlacementDistance, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.planeEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = placementMode.instantPlacementEnabled): HitResult?

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
| xPx | x view coordinate in pixels By default the placementPosition of this Node is used |
