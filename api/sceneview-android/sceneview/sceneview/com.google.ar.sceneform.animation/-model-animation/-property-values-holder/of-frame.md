//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimation](../index.md)/[PropertyValuesHolder](index.md)/[ofFrame](of-frame.md)

# ofFrame

[androidJvm]\
open fun [ofFrame](of-frame.md)(frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)

Constructs and returns a PropertyValuesHolder with a given set of frame values. **Warning** Every PropertyValuesHolder that applies a modification on the time position of the animation should use the ModelAnimation.TIME_POSITION instead of its own Property in order to possibly cancel any ObjectAnimator operating time modifications on the same ModelAnimation. [setAutoCancel](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html#setAutoCancel-boolean-) will have no effect for different property names 

 That's why we avoid using an ModelAnimation.FRAME_POSITION or ModelAnimation.FRACTION_POSITION Property

#### Return

PropertyValuesHolder The constructed PropertyValuesHolder object.

## Parameters

androidJvm

| | |
|---|---|
| frames | The frames that the [ModelAnimation](../index.md) will animate between. |
