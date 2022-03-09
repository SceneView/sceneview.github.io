//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)/[ofAllAnimations](of-all-animations.md)

# ofAllAnimations

[androidJvm]\
open fun [ofAllAnimations](of-all-animations.md)(model: [AnimatableModel](../-animatable-model/index.md)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for all [ModelAnimation](../-model-animation/index.md) inside an [AnimatableModel](../-animatable-model/index.md). **The setAutoCancel(true) won't work**

Don't forget to call start

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [ofAnimation(AnimatableModel, ModelAnimation...)](of-animation.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted model to animate |
