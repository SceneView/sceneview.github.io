//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[pickNode](pick-node.md)

# pickNode

[androidJvm]\
fun [pickNode](pick-node.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), onResult: (pickingResult: [SceneView.PickingResult](-picking-result/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Picks a node at given coordinates

Filament picking works with a small delay, therefore, a callback is used. If no node is picked, the callback is invoked with a `null` value instead of a node.

## Parameters

androidJvm

| | |
|---|---|
| x | The x coordinate within the `SceneView`. |
| y | The y coordinate within the `SceneView`. |
| onResult | Called when picking completes. |

[androidJvm]\
fun [pickNode](pick-node.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), onResult: (pickingResult: [SceneView.PickingResult](-picking-result/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Picks a node at given motion event

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.SceneView](pick-node.md) |  |
