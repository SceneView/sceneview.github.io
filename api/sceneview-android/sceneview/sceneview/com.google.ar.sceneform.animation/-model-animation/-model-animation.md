//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimation](index.md)/[ModelAnimation](-model-animation.md)

# ModelAnimation

[androidJvm]\
open fun [ModelAnimation](-model-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

ModelAnimation constructed from an Animator

## Parameters

androidJvm

| | |
|---|---|
| name | This name should corresponds to the one defined and exported in the [AnimatableModel](../-animatable-model/index.md). Typically the action name defined in the 3D creation software. |
| index | Zero-based index of the target `animation` as defined in the original [AnimatableModel](../-animatable-model/index.md) |
| duration | This original [AnimatableModel](../-animatable-model/index.md) duration |
| frameRate | The frames per second defined in the original animation asset |
