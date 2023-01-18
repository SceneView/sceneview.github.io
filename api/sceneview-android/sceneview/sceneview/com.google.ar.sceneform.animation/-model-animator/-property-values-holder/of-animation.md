//[sceneview](../../../../index.md)/[com.google.ar.sceneform.animation](../../index.md)/[ModelAnimator](../index.md)/[PropertyValuesHolder](index.md)/[ofAnimation](of-animation.md)

# ofAnimation

[androidJvm]\
open fun [ofAnimation](of-animation.md)(animation: [ModelAnimation](../../-model-animation/index.md)): [PropertyValuesHolder](https://developer.android.com/reference/kotlin/android/animation/PropertyValuesHolder.html)

Constructs and returns a PropertyValuesHolder for a targeted [ModelAnimation](../../-model-animation/index.md). This method applies by default this to the returned ObjectAnimator : 

- The duration value to the [getDuration](../../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-duration.md) in order to match the original animation speed.
- The interpolator to [LinearInterpolator](https://developer.android.com/reference/kotlin/android/view/animation/LinearInterpolator.html) in order to match the natural animation interpolation.

#### Return

The constructed PropertyValuesHolder object.

## Parameters

androidJvm

| | |
|---|---|
| animation | The animation of interest |
