//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[ModelAnimation](index.md)

# ModelAnimation

[androidJvm]\
open class [ModelAnimation](index.md)

An ModelAnimation is a reusable set of keyframe tracks which represent an animation. 

 This class provides support for animating time positions on a targeted [AnimatableModel](../-animatable-model/index.md)

## Here are some use cases for animations :

- On a very basic 3D model like a single infinite rotating sphere, you should not have to use this class but probably instead just call animate
- For a synchronised animation set like animating a cube and a sphere position and rotation at same time or sequentially, please consider using an [android.animation.AnimatorSet](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html) playing a [ofAnimation](../-model-animator/of-animation.md) or [ofPropertyValuesHolder](../-model-animator/of-property-values-holder.md)
- If the mesh is a character, for example, there may be one ModelAnimation for a walkcycle, a second for a jump, a third for sidestepping and so on. Assuming a character object has a skeleton, one keyframe track could store the data for the position changes of the lower arm bone over time, a different track the data for the rotation changes of the same bone, a third the track position, rotation or scaling of another bone, and so on. It should be clear, that an ModelAnimation can act on lots of such tracks. Assuming the model has morph targets (for example one morph target showing a friendly face and another showing an angry face), each track holds the information as to how the influence of a certain morph target changes during the performance of the clip. In this case you should manage one [android.animation.ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) coming from [ofAnimation](../-model-animator/of-animation.md) per action. And an [android.animation.AnimatorSet](https://developer.android.com/reference/kotlin/android/animation/AnimatorSet.html) to play them sequentially or together.

## Constructors

| | |
|---|---|
| [ModelAnimation](-model-animation.md) | [androidJvm]<br>open fun [ModelAnimation](-model-animation.md)(model: [AnimatableModel](../-animatable-model/index.md), name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>ModelAnimation constructed from an Animator |

## Types

| Name | Summary |
|---|---|
| [PropertyValuesHolder](-property-values-holder/index.md) | [androidJvm]<br>open class [PropertyValuesHolder](-property-values-holder/index.md)<br>This class holds information about a property and the values that that property should take during an animation. |

## Functions

| Name | Summary |
|---|---|
| [fractionToTime](fraction-to-time.md) | [androidJvm]<br>open fun [fractionToTime](fraction-to-time.md)(fraction: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), duration: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the elapsed time in seconds of a fraction position |
| [frameToTime](frame-to-time.md) | [androidJvm]<br>open fun [frameToTime](frame-to-time.md)(frame: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the elapsed time in seconds of a frame position |
| [geIndex](ge-index.md) | [androidJvm]<br>open fun [geIndex](ge-index.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns The Zero-based index of the target `animation` as defined in the original [AnimatableModel](../-animatable-model/index.md) |
| [getDurationMillis](get-duration-millis.md) | [androidJvm]<br>open fun [getDurationMillis](get-duration-millis.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Returns the duration of this animation in milliseconds. |
| [getFractionAtTime](get-fraction-at-time.md) | [androidJvm]<br>open fun [getFractionAtTime](get-fraction-at-time.md)(time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the fraction position at the elapsed time in seconds. |
| [getFractionPosition](get-fraction-position.md) | [androidJvm]<br>open fun [getFractionPosition](get-fraction-position.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the fractional value at the current animation position. |
| [getFrameAtTime](get-frame-at-time.md) | [androidJvm]<br>open fun [getFrameAtTime](get-frame-at-time.md)(time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get the frame position at the elapsed time in seconds. |
| [getFrameCount](get-frame-count.md) | [androidJvm]<br>open fun [getFrameCount](get-frame-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the total number of frames of this animation. |
| [getFramePosition](get-frame-position.md) | [androidJvm]<br>open fun [getFramePosition](get-frame-position.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get the current frame number at the current animation position. |
| [getTimeAtFraction](get-time-at-fraction.md) | [androidJvm]<br>open fun [getTimeAtFraction](get-time-at-fraction.md)(fraction: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the elapsed time in seconds of a fraction position |
| [getTimeAtFrame](get-time-at-frame.md) | [androidJvm]<br>open fun [getTimeAtFrame](get-time-at-frame.md)(frame: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the elapsed time in seconds of a frame position |
| [secondsToMillis](seconds-to-millis.md) | [androidJvm]<br>open fun [secondsToMillis](seconds-to-millis.md)(time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Convert time in seconds to time in millis |
| [setFractionPosition](set-fraction-position.md) | [androidJvm]<br>open fun [setFractionPosition](set-fraction-position.md)(fractionPosition: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Sets the current position of (seeks) the animation to the specified fraction position. |
| [setFramePosition](set-frame-position.md) | [androidJvm]<br>open fun [setFramePosition](set-frame-position.md)(frameNumber: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Sets the current position of (seeks) the animation to the specified frame number according to the [getFrameRate](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-frame-rate.md). |
| [timeToFraction](time-to-fraction.md) | [androidJvm]<br>open fun [timeToFraction](time-to-fraction.md)(time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), duration: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the fraction position at the elapsed time in seconds. |
| [timeToFrame](time-to-frame.md) | [androidJvm]<br>open fun [timeToFrame](time-to-frame.md)(time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get the frame position at the elapsed time in seconds. |

## Properties

| Name | Summary |
|---|---|
| [duration](duration.md) | [androidJvm]<br>open val [duration](duration.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [FRACTION_POSITION](-f-r-a-c-t-i-o-n_-p-o-s-i-t-i-o-n.md) | [androidJvm]<br>val [FRACTION_POSITION](-f-r-a-c-t-i-o-n_-p-o-s-i-t-i-o-n.md): [Property](https://developer.android.com/reference/kotlin/android/util/Property.html)&lt;[ModelAnimation](index.md), [Float](https://developer.android.com/reference/kotlin/java/lang/Float.html)&gt;<br>A Property wrapper around the `fractionPosition` functionality handled by the [setFractionPosition](set-fraction-position.md) and [getFractionPosition](get-fraction-position.md) methods |
| [FRAME_POSITION](-f-r-a-m-e_-p-o-s-i-t-i-o-n.md) | [androidJvm]<br>val [FRAME_POSITION](-f-r-a-m-e_-p-o-s-i-t-i-o-n.md): [Property](https://developer.android.com/reference/kotlin/android/util/Property.html)&lt;[ModelAnimation](index.md), [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)&gt;<br>A Property wrapper around the `framePosition` functionality handled by the [setFramePosition](set-frame-position.md) and [getFramePosition](get-frame-position.md) methods |
| [frameRate](frame-rate.md) | [androidJvm]<br>open val [frameRate](frame-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isDirty](is-dirty.md) | [androidJvm]<br>open var [isDirty](is-dirty.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [name](name.md) | [androidJvm]<br>open val [name](name.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [TIME_POSITION](-t-i-m-e_-p-o-s-i-t-i-o-n.md) | [androidJvm]<br>val [TIME_POSITION](-t-i-m-e_-p-o-s-i-t-i-o-n.md): [FloatProperty](https://developer.android.com/reference/kotlin/android/util/FloatProperty.html)&lt;[ModelAnimation](index.md)&gt;<br>A Property wrapper around the `timePosition` functionality handled by the [setTimePosition](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/set-time-position.md) and [getTimePosition](../../../../sceneview/com.google.ar.sceneform.animation/-model-animation/get-time-position.md) methods. |
| [timePosition](time-position.md) | [androidJvm]<br>open var [timePosition](time-position.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Time position is applied inside a global [android.view.Choreographer](https://developer.android.com/reference/kotlin/android/view/Choreographer.html) frame callback to ensure that the transformations are applied in a hierarchical order. |
