//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[AnimatableModel](index.md)/[setAnimationsFramePosition](set-animations-frame-position.md)

# setAnimationsFramePosition

[androidJvm]\
open fun [setAnimationsFramePosition](set-animations-frame-position.md)(framePosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Sets the current position of (seeks) all the animations to the specified frame number according to the [getFrameRate](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-frame-rate.md)

 This method will apply rotation, translation, and scale to the Renderable that have been targeted. Uses TransformManager

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimation](../-model-animation/get-frame-count.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| framePosition | Frame number on the timeline. Between 0 and [getFrameCount](../-model-animation/get-frame-count.md). |
