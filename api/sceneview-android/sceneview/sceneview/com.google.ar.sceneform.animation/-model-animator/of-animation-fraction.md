//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)/[ofAnimationFraction](of-animation-fraction.md)

# ofAnimationFraction

[androidJvm]\
open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of fraction values. 

Don't forget to call start

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [ofAnimationFraction(AnimatableModel, ModelAnimation, float...)](of-animation-fraction.md) |  |
| [com.google.ar.sceneform.animation.ModelAnimation](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-name.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted model to animate |
| animationName | The string name of the animation. This name should correspond to the one defined and exported in the model. Typically the action name defined in the 3D creation software. [getName](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-name.md) |
| fractions | The fractions (percentage) (between 0 and 1) |

[androidJvm]\
open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of fraction values. 

Don't forget to call start

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [ofAnimationFraction(AnimatableModel, ModelAnimation, float...)](of-animation-fraction.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted model to animate |
| animationIndex | Zero-based index for the animation of interest. |
| fractions | The fractions (percentage) (between 0 and 1) |

[androidJvm]\
open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animation: [ModelAnimation](../-model-animation/index.md), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of fraction values. 

- A single value implies that that value is the one being animated to starting from the actual value on the provided [ModelAnimation](../-model-animation/index.md).
- Two values imply a starting and ending values.
- More than two values imply a starting value, values to animate through along the way, and an ending value (these values will be distributed evenly across the duration of the animation).

 The properties (time, frame,... position) are applied to the [AnimatableModel](../-animatable-model/index.md) This method applies by default this to the returned ObjectAnimator : 

- The duration value to the [getDuration](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) in order to match the original animation speed.
- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

Don't forget to call start

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [ofAnimationTime(AnimatableModel, ModelAnimation, float...)](of-animation-time.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted model to animate |
| animation | The animation of interest |
| fractions | The fractions (percentage) (between 0 and 1) |
