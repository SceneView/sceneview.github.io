//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)/[ofAnimation](of-animation.md)

# ofAnimation

[androidJvm]\
open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animationNames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a given name inside an [AnimatableModel](../-animatable-model/index.md). **The setAutoCancel(true) won't work for new call with different animations.**

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
| animationNames | The string names of the animations. This name should correspond to the one defined and exported in the model. Typically the action name defined in the 3D creation software. [getName](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-name.md) |

[androidJvm]\
open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndexes: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a given index inside an [AnimatableModel](../-animatable-model/index.md). **The setAutoCancel(true) won't work for new call with different animations.**

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
| model | The targeted animatable to animate |
| animationIndexes | Zero-based indexes for the animations of interest. |

[androidJvm]\
open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animations: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelAnimation](../-model-animation/index.md)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for a targeted [ModelAnimation](../-model-animation/index.md) inside an [AnimatableModel](../-animatable-model/index.md). **The setAutoCancel(true) won't work for new call with different animations.** This method applies by default this to the returned ObjectAnimator : 

- The duration value to the max [getDuration](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) in order to match the original animation speed.
- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

Don't forget to call start

#### Return

The constructed ObjectAnimator

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted animatable to animate |
| animations | The animations of interest |
