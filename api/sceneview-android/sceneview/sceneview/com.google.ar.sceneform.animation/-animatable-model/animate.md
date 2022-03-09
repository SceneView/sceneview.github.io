//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[AnimatableModel](index.md)/[animate](animate.md)

# animate

[androidJvm]\
open fun [animate](animate.md)(repeat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for all [ModelAnimation](../-model-animation/index.md) of this object. 

Don't forget to call

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimator](../-model-animator/of-animation-time.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| repeat | repeat/loop the animation |

[androidJvm]\
open fun [animate](animate.md)(animationNames: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a given name of this object. **Don't forget to call** **start**

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimator](../-model-animator/of-animation-time.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| animationNames | The string names of the animations. This name should correspond to the one defined and exported in the model. Typically the action name defined in the 3D creation software. [getName](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-name.md) |

[androidJvm]\
open fun [animate](animate.md)(animationIndexes: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for targeted [ModelAnimation](../-model-animation/index.md) with a a given index of this object. **Don't forget to call** **start**

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimator](../-model-animator/of-animation-time.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| animationIndexes | Zero-based indexes for the animations of interest. |

[androidJvm]\
open fun [animate](animate.md)(animations: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelAnimation](../-model-animation/index.md)&gt;): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)

Constructs and returns an [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) for a targeted [ModelAnimation](../-model-animation/index.md) of this object. **The setAutoCancel(true) won't work for new call with different animations.**This method applies by default this to the returned ObjectAnimator : 

- The duration value to the max [getDuration](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) in order to match the original animation speed.
- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

**Don't forget to call** **start**

#### Return

The constructed ObjectAnimator

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.animation.ModelAnimator](../-model-animator/of-animation-time.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| animations | The animations of interest |
