//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[hitTest](hit-test.md)

# hitTest

[androidJvm]\
fun [hitTest](hit-test.md)(position: [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md), plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): HitResult?

[androidJvm]\
fun [hitTest](hit-test.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), approximateDistance: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f): HitResult?

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
| xPx | x view coordinate in pixels |
