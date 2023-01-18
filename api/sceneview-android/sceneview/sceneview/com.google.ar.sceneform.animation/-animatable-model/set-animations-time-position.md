//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[AnimatableModel](index.md)/[setAnimationsTimePosition](set-animations-time-position.md)

# setAnimationsTimePosition

[androidJvm]\
open fun [setAnimationsTimePosition](set-animations-time-position.md)(timePosition: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Sets the current position of (seeks) the animation to the specified time position in seconds. This time should be 

 This method will apply rotation, translation, and scale to the Renderable that have been targeted. Uses `TransformManager`

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimation](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| timePosition | Elapsed time of interest in seconds. Between 0 and the max value of [getDuration](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md). |
