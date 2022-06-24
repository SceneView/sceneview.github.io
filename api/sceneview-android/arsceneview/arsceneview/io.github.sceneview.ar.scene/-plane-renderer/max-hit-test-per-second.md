//[arsceneview](../../../index.md)/[io.github.sceneview.ar.scene](../index.md)/[PlaneRenderer](index.md)/[maxHitTestPerSecond](max-hit-test-per-second.md)

# maxHitTestPerSecond

[androidJvm]\
var [maxHitTestPerSecond](max-hit-test-per-second.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 10

###  Adjust the max screen [ArFrame.hitTest](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) number per seconds

Decrease if you don't need a very precise position update and want to reduce frame consumption. Increase for a more accurate positioning update.
