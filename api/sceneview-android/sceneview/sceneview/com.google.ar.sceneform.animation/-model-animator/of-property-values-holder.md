//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)/[ofPropertyValuesHolder](of-property-values-holder.md)

# ofPropertyValuesHolder

[androidJvm]\
open fun [ofPropertyValuesHolder](of-property-values-holder.md)(model: [AnimatableModel](../-animatable-model/index.md), values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an ObjectAnimator a [ModelAnimation](../-model-animation/index.md) applying PropertyValuesHolders. 

- A single value implies that that value is the one being animated to starting from the actual value on the provided [ModelAnimation](../-model-animation/index.md).
- Two values imply a starting and ending values.
- More than two values imply a starting value, values to animate through along the way, and an ending value (these values will be distributed evenly across the duration of the animation).

 The properties (time, frame,... position) are applied to the [AnimatableModel](../-animatable-model/index.md)This method applies by default this to the returned ObjectAnimator : 

- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

Don't forget to call start

#### Return

The constructed ObjectAnimator

## Parameters

androidJvm

| | |
|---|---|
| model | The targeted model to animate |
| values | A set of PropertyValuesHolder objects whose values will be animated between over time. |
