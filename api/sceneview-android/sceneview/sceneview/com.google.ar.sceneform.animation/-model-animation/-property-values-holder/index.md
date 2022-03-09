//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimation](../index.md)/[PropertyValuesHolder](index.md)

# PropertyValuesHolder

[androidJvm]\
open class [PropertyValuesHolder](index.md)

This class holds information about a property and the values that that property should take during an animation. PropertyValuesHolder objects can be used to create animations with ObjectAnimator or that operate on several different properties in parallel. 

 Using this [PropertyValuesHolder](index.md) provide an handled [ModelAnimator](../../-model-animator/index.md) canceling since we target a same object and those PropertyValuesHolder have the same property name

## Functions

| Name | Summary |
|---|---|
| [ofFraction](of-fraction.md) | [androidJvm]<br>open fun [ofFraction](of-fraction.md)(fractions: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder with a given set of fraction values. |
| [ofFrame](of-frame.md) | [androidJvm]<br>open fun [ofFrame](of-frame.md)(frames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder with a given set of frame values. |
| [ofTime](of-time.md) | [androidJvm]<br>open fun [ofTime](of-time.md)(times: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt;): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)<br>Constructs and returns a PropertyValuesHolder with a given set of time values. |
