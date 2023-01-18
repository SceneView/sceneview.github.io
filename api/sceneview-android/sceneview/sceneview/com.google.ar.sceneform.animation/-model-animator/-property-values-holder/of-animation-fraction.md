//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimator](../index.md)/[PropertyValuesHolder](index.md)/[ofAnimationFraction](of-animation-fraction.md)

# ofAnimationFraction

[androidJvm]\
open fun [ofAnimationFraction](of-animation-fraction.md)(animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)

Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of fraction values.

#### Return

The constructed PropertyValuesHolder object.

## See also

androidJvm

| | |
|---|---|
| [ofAnimationFraction(ModelAnimation, float...)](of-animation-fraction.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| animationName | The string name of the animation. This name should correspond to the one defined and exported in the model. Typically the action name defined in the 3D creation software. [getName](../../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-name.md) |
| fractions | The fractions (percentage) (between 0 and 1) |

[androidJvm]\
open fun [ofAnimationFraction](of-animation-fraction.md)(animation: [ModelAnimation](../../-model-animation/index.md), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)

Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of fraction values. 

- A single value implies that that value is the one being animated to starting from the actual value on the provided [ModelAnimation](../../-model-animation/index.md).
- Two values imply a starting and ending values.
- More than two values imply a starting value, values to animate through along the way, and an ending value (these values will be distributed evenly across the duration of the animation).

 The properties (time, frame,... position) are applied to the [AnimatableModel](../../-animatable-model/index.md)This method applies by default this to the returned ObjectAnimator : 

- The duration value to the [getDuration](../../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) in order to match the original animation speed.
- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

#### Return

The constructed PropertyValuesHolder object.

## Parameters

androidJvm

| | |
|---|---|
| animation | The animation of interest |
| fractions | The fractions (percentage) (between 0 and 1) |
