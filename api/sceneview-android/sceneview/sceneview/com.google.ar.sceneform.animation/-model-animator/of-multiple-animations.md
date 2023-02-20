//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)/[ofMultipleAnimations](of-multiple-animations.md)

# ofMultipleAnimations

[androidJvm]\
open fun [ofMultipleAnimations](of-multiple-animations.md)(model: [AnimatableModel](../-animatable-model/index.md), animationNames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)&gt;

Constructs and returns list of [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) given names inside an [AnimatableModel](../-animatable-model/index.md). Can be used directly with [playTogether](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html#playTogether-java.util.Collection&lt;android.animation.Animator&gt;-)[playSequentially](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html#playSequentially-java.util.List&lt;android.animation.Animator&gt;-)

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
