//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[TransformComponent](index.md)/[lookAt](look-at.md)

# lookAt

[androidJvm]\
open fun [lookAt](look-at.md)(eye: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = worldPosition, targetPosition: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

Rotate the transform to face a point in world-space.

## Parameters

androidJvm

| | |
|---|---|
| targetPosition | The target position to look at in world space |
| smooth | Whether the rotation should happen smoothly |

[androidJvm]\
open fun [lookAt](look-at.md)(eye: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = worldPosition, targetComponent: [TransformComponent](index.md), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

Rotates the transform to face another [TransformComponent](index.md).

## Parameters

androidJvm

| | |
|---|---|
| targetComponent | The target [TransformComponent](index.md) to look at |
| smooth | Whether the rotation should happen smoothly |
