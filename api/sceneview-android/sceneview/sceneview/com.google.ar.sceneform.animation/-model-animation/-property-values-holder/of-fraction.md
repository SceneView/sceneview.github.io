//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimation](../index.md)/[PropertyValuesHolder](index.md)/[ofFraction](of-fraction.md)

# ofFraction

[androidJvm]\
open fun [ofFraction](of-fraction.md)(fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)

Constructs and returns a PropertyValuesHolder with a given set of fraction values. **Warning** Every PropertyValuesHolder that applies a modification on the time position of the animation should use the ModelAnimation.TIME_POSITION instead of its own Property in order to possibly cancel any ObjectAnimator operating time modifications on the same ModelAnimation. [setAutoCancel](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html#setAutoCancel-boolean-) will have no effect for different property names 

 That's why we avoid using an ModelAnimation.FRAME_POSITION or ModelAnimation.FRACTION_POSITION Property

#### Return

PropertyValuesHolder The constructed PropertyValuesHolder object.

## Parameters

androidJvm

| | |
|---|---|
| fractions | The fractions that the [ModelAnimation](../index.md) will animate between. |
