//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[lookAt](look-at.md)

# lookAt

[androidJvm]\
fun [lookAt](look-at.md)(targetPosition: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623), upDirection: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) = Direction(y = 1.0f), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

###  Rotates the node to face a point in world-space

## Parameters

androidJvm

| | |
|---|---|
| targetPosition | The target position to look at in world space |
| upDirection | The up direction will determine the orientation of the node around the direction |
| smooth | Whether the rotation should happen smoothly |

[androidJvm]\
fun [lookAt](look-at.md)(targetNode: [Node](index.md), upDirection: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) = Direction(y = 1.0f), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

###  Rotates the node to face another node

## Parameters

androidJvm

| | |
|---|---|
| targetNode | The target node to look at |
| upDirection | The up direction will determine the orientation of the node around the direction |
| smooth | Whether the rotation should happen smoothly |
