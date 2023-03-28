//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimator](index.md)

# ModelAnimator

[androidJvm]\
open class [ModelAnimator](index.md)

This class provides support for animating an [AnimatableModel](../-animatable-model/index.md)

## Usage

 By default the [ModelAnimator](index.md) can play the full [ModelAnimation](../-model-animation/index.md) starting from 0 to the animation duration with: 

```kotlin

```

 If you want to specify a start and end, you should use: 

```kotlin

```
```kotlin

```
```kotlin

```

## Use cases

### Simple usage

 On a very basic 3D model like a single infinite rotating sphere, you should not have to use [ModelAnimator](index.md) but probably instead just call: 

```kotlin

```

### Single Model with Single Animation

 If you want to animate a single model to a specific timeline position, use: 

```kotlin

```
```kotlin

```
```kotlin

```

- A single time, frame, fraction value will go from the actual position to the desired one
- Two values means form value1 to value2
- More than two values means form value1 to value2 then to value3

*Example:*```kotlin
ModelAnimator.ofAnimationFraction(model, "VerticalTranslation", 0f, 0.8f, 0f).start();

```

### Single Model with Multiple Animations

 If the model is a character, for example, there may be one ModelAnimation for a walkcycle, a second for a jump, a third for sidestepping and so on. 

```kotlin

```
```kotlin

```
*Example:*

 Here you can see that no call to `animator.cancel()` is required because the `animator.setAutoCancel(boolean)` is set to true by default. 

```kotlin
ObjectAnimator walkAnimator = ModelAnimator.ofAnimation(model, "walk");
walkButton.setOnClickListener(v -> walkAnimator.start());

ObjectAnimator runAnimator = ModelAnimator.ofAnimation(model, "run");
runButton.setOnClickListener(v -> runAnimator.start());

```
*or sequentially:*```kotlin
AnimatorSet animatorSet = new AnimatorSet();
animatorSet.playSequentially(ModelAnimator.ofMultipleAnimations(model, "walk", "run"));
animatorSet.start();

```

### Multiple Models with Multiple Animations

 For a synchronised animation set like animating a complete scene with multiple models time or sequentially, please consider using an [android.animation.AnimatorSet](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html) with one [ModelAnimator](index.md) parametrized per step : 

*Example:*```kotlin
AnimatorSet completeFly = new AnimatorSet();

ObjectAnimator liftOff = ModelAnimator.ofAnimationFraction(airPlaneModel, "FlyAltitude",0, 40);
liftOff.setInterpolator(new AccelerateInterpolator());

AnimatorSet flying = new AnimatorSet();
ObjectAnimator flyAround = ModelAnimator.ofAnimation(airPlaneModel, "FlyAround");
flyAround.setRepeatCount(ValueAnimator.INFINITE);
flyAround.setDuration(10000);
ObjectAnimator airportBusHome = ModelAnimator.ofAnimationFraction(busModel, "Move", 0);
flying.playTogether(flyAround, airportBusHome);

ObjectAnimator land = ModelAnimator.ofAnimationFraction(airPlaneModel, "FlyAltitude", 0);
land.setInterpolator(new DecelerateInterpolator());

completeFly.playSequentially(liftOff, flying, land);

```

### Morphing animation

 Assuming a character object has a skeleton, one keyframe track could store the data for the position changes of the lower arm bone over time, a different track the data for the rotation changes of the same bone, a third the track position, rotation or scaling of another bone, and so on. It should be clear, that an ModelAnimation can act on lots of such tracks. 

 Assuming the model has morph targets (for example one morph target showing a friendly face and another showing an angry face), each track holds the information as to how the influence of a certain morph target changes during the performance of the clip. 

 In a glTF context, this [Animator](https://developer.android.com/reference/kotlin/android/animation/Animator.html) updates matrices according to glTF `animation` and `skin` definitions. 

### [ModelAnimator](index.md) can be used for two things

- Updating matrices in `TransformManager` components according to the model `animation` definitions.
- Updating bone matrices in `RenderableManager` components according to the model `skin` definitions.

 Every PropertyValuesHolder that applies a modification on the time position of the animation must use the ModelAnimation.TIME_POSITION instead of its own Property in order to possibly cancel any ObjectAnimator operating time modifications on the same ModelAnimation. 

 More information about Animator: [ https://developer.android.com/guide/topics/graphics/prop-animation ](https://developer.android.com/guide/topics/graphics/prop-animation)

## Types

| Name | Summary |
|---|---|
| [PropertyValuesHolder](-property-values-holder/index.md) | [androidJvm]<br>open class [PropertyValuesHolder](-property-values-holder/index.md)<br>This class holds information about a property and the values that that property should take during an animation. |

## Functions

| Name | Summary |
|---|---|
| [ofAllAnimations](of-all-animations.md) | [androidJvm]<br>open fun [ofAllAnimations](of-all-animations.md)(model: [AnimatableModel](../-animatable-model/index.md)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for all [ModelAnimation](../-model-animation/index.md) inside an [AnimatableModel](../-animatable-model/index.md). |
| [ofAnimation](of-animation.md) | [androidJvm]<br>open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animations: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelAnimation](../-model-animation/index.md)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for a targeted [ModelAnimation](../-model-animation/index.md) inside an [AnimatableModel](../-animatable-model/index.md).<br>[androidJvm]<br>open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndexes: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a given index inside an [AnimatableModel](../-animatable-model/index.md).<br>[androidJvm]<br>open fun [ofAnimation](of-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), animationNames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a given name inside an [AnimatableModel](../-animatable-model/index.md). |
| [ofAnimationFraction](of-animation-fraction.md) | [androidJvm]<br>open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animation: [ModelAnimation](../-model-animation/index.md), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationFraction](of-animation-fraction.md)(model: [AnimatableModel](../-animatable-model/index.md), animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of fraction values. |
| [ofAnimationFrame](of-animation-frame.md) | [androidJvm]<br>open fun [ofAnimationFrame](of-animation-frame.md)(model: [AnimatableModel](../-animatable-model/index.md), animation: [ModelAnimation](../-model-animation/index.md), frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationFrame](of-animation-frame.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationFrame](of-animation-frame.md)(model: [AnimatableModel](../-animatable-model/index.md), animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of frame values. |
| [ofAnimationTime](of-animation-time.md) | [androidJvm]<br>open fun [ofAnimationTime](of-animation-time.md)(model: [AnimatableModel](../-animatable-model/index.md), animation: [ModelAnimation](../-model-animation/index.md), times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationTime](of-animation-time.md)(model: [AnimatableModel](../-animatable-model/index.md), animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>open fun [ofAnimationTime](of-animation-time.md)(model: [AnimatableModel](../-animatable-model/index.md), animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an ObjectAnimator clipping a [ModelAnimation](../-model-animation/index.md) to a given set of time values. |
| [ofMultipleAnimations](of-multiple-animations.md) | [androidJvm]<br>open fun [ofMultipleAnimations](of-multiple-animations.md)(model: [AnimatableModel](../-animatable-model/index.md), animationNames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)&gt;<br>Constructs and returns list of [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) given names inside an [AnimatableModel](../-animatable-model/index.md). |
| [ofPropertyValuesHolder](of-property-values-holder.md) | [androidJvm]<br>open fun [ofPropertyValuesHolder](of-property-values-holder.md)(model: [AnimatableModel](../-animatable-model/index.md), values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)<br>Constructs and returns an ObjectAnimator a [ModelAnimation](../-model-animation/index.md) applying PropertyValuesHolders. |
