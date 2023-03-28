//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimator](../index.md)/[PropertyValuesHolder](index.md)

# PropertyValuesHolder

[androidJvm]\
open class [PropertyValuesHolder](index.md)

This class holds information about a property and the values that that property should take during an animation. 

PropertyValuesHolder objects can be used to create animations with ObjectAnimator or that operate on several different properties in parallel.

## Warning:

Using this PropertyValuesHolder is very useful for targeting multiple time or frame properties of multiple animations inside a same ObjectAnimator model

**and** insure a less consuming [android.view.Choreographer.FrameCallback](https://developer.android.com/reference/kotlin/android/view/Choreographer.FrameCallback.html) than using [playTogether](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html#playtogether)

**but** If you want to use the [setAutoCancel](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html#setautocancel) functionality, you have to take care of this :

```kotlin
ObjectAnimator.hasSameTargetAndProperties(Animator anim) {
     PropertyValuesHolder[] theirValues = ((ObjectAnimator) anim).getValues();
     if (((ObjectAnimator) anim).getTarget() == getTarget() &&
             mValues.length == theirValues.length) {
         for (int i = 0; i < mValues.length; ++i) {
             PropertyValuesHolder pvhMine = mValues[i];
             PropertyValuesHolder pvhTheirs = theirValues[i];
             if (pvhMine.getPropertyName() == null ||
                     !pvhMine.getPropertyName().equals(pvhTheirs.getPropertyName())) {
                 return false;
             }
         }
         return true;
     }
 }

```

## See also

androidJvm

| | |
|---|---|
| [android.animation.ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |  |

## Functions

| Name | Summary |
|---|---|
| [ofAnimation](of-animation.md) | [androidJvm]<br>open fun [ofAnimation](of-animation.md)(animation: [ModelAnimation](../../-model-animation/index.md)): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md). |
| [ofAnimationFraction](of-animation-fraction.md) | [androidJvm]<br>open fun [ofAnimationFraction](of-animation-fraction.md)(animation: [ModelAnimation](../../-model-animation/index.md), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>open fun [ofAnimationFraction](of-animation-fraction.md)(animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of fraction values. |
| [ofAnimationFrame](of-animation-frame.md) | [androidJvm]<br>open fun [ofAnimationFrame](of-animation-frame.md)(animation: [ModelAnimation](../../-model-animation/index.md), frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of frame values.<br>[androidJvm]<br>open fun [ofAnimationFrame](of-animation-frame.md)(animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of fame values. |
| [ofAnimationTime](of-animation-time.md) | [androidJvm]<br>open fun [ofAnimationTime](of-animation-time.md)(animation: [ModelAnimation](../../-model-animation/index.md), times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md) with a given set of time values.<br>[androidJvm]<br>open fun [ofAnimationTime](of-animation-time.md)(animationName: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder for a targeted animation set of time values. |
