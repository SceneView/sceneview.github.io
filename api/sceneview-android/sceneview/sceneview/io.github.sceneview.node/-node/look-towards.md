//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[lookTowards](look-towards.md)

# lookTowards

[androidJvm]\
fun [lookTowards](look-towards.md)(lookDirection: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623), upDirection: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) = Direction(y = 1.0f), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

###  Rotates the node to face a direction in world-space

The look direction and up direction cannot be coincident (parallel) or the orientation will be invalid.

## Parameters

androidJvm

| | |
|---|---|
| lookDirection | The desired look direction in world-space |
| upDirection | The up direction will determine the orientation of the node around the look direction |
| smooth | Whether the rotation should happen smoothly |
