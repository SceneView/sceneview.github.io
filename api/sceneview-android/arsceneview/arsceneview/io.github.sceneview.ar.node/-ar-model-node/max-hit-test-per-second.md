//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[maxHitTestPerSecond](max-hit-test-per-second.md)

# maxHitTestPerSecond

[androidJvm]\
var [maxHitTestPerSecond](max-hit-test-per-second.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 10

###  Adjust the max screen [ArFrame.hitTest](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) number per seconds

When this node is not anchored and [followHitPosition](follow-hit-position.md) is set to true, the node will constantly try to find its place in real world. Following the [hitPosition](hit-position.md) on the screen.

Decrease if you don't need a very precise position update and want to reduce frame consumption. Increase for a more accurate positioning update.
