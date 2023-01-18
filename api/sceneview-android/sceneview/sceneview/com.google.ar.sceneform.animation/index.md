//[sceneview](../../index.md)/[com.google.ar.sceneform.animation](index.md)

# Package com.google.ar.sceneform.animation

## Types

| Name | Summary |
|---|---|
| [AnimatableModel](-animatable-model/index.md) | [androidJvm]<br>interface [AnimatableModel](-animatable-model/index.md)<br>An AnimatableModel is an object whose properties can be animated by an [ModelAnimation](-model-animation/index.md). |
| [ModelAnimation](-model-animation/index.md) | [androidJvm]<br>open class [ModelAnimation](-model-animation/index.md)<br>An ModelAnimation is a reusable set of keyframe tracks which represent an animation. |
| [ModelAnimator](-model-animator/index.md) | [androidJvm]<br>open class [ModelAnimator](-model-animator/index.md)<br>This class provides support for animating an [AnimatableModel](-animatable-model/index.md)<br>Usage<br> By default the [ModelAnimator](-model-animator/index.md) can play the full [ModelAnimation](-model-animation/index.md) starting from 0 to the animation duration with: ```kotlin<br>```  If you want to specify a start and end, you should use: ```kotlin<br>``` ```kotlin<br>``` ```kotlin<br>```<br>Use cases<br>Simple usage<br> On a very basic 3D model like a single infinite rotating sphere, you should not have to use [ModelAnimator](-model-animator/index.md) but probably instead just call: ```kotlin<br>```<br>Single Model with Single Animation<br> If you want to animate a single model to a specific timeline position, use: ```kotlin<br>``` ```kotlin<br>``` ```kotlin<br>```<br>- A single time, frame, fraction value will go from the actual position to the desired one - Two values means form value1 to value2 - More than two values means form value1 to value2 then to value3<br>*Example:*```kotlin ModelAnimator.ofAnimationFraction(model, "VerticalTranslation", 0f, 0.8f, 0f).start();<br>```<br>Single Model with Multiple Animations<br> If the model is a character, for example, there may be one ModelAnimation for a walkcycle, a second for a jump, a third for sidestepping and so on. |
