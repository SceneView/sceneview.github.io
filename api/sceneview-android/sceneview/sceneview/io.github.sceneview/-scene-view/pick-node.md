//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[pickNode](pick-node.md)

# pickNode

[androidJvm]\
fun [pickNode](pick-node.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), onPickingCompleted: (node: [ModelNode](../../io.github.sceneview.node/-model-node/index.md)?, [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Picks a node at given coordinates

Filament picking works with a small delay, therefore, a callback is used. If no node is picked, the callback is invoked with a null value instead of a node.

## Parameters

androidJvm

| | |
|---|---|
| x | The x coordinate within the SceneView. |
| y | The y coordinate within the SceneView. |
| onPickingCompleted | Called when picking completes. |

[androidJvm]\
fun [pickNode](pick-node.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), onPickingCompleted: (e: [NodeMotionEvent](../../io.github.sceneview.gesture/-node-motion-event/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))
