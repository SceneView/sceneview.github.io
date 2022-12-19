//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[TransformComponent](index.md)/[lookTowards](look-towards.md)

# lookTowards

[androidJvm]\
open fun [lookTowards](look-towards.md)(lookDirection: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623), smooth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

Rotates the transform to face a direction in world-space.

The look direction and up direction cannot be coincident (parallel) or the orientation will be invalid.

## Parameters

androidJvm

| | |
|---|---|
| lookDirection | The desired look direction in world-space |
| smooth | Whether the rotation should happen smoothly |
