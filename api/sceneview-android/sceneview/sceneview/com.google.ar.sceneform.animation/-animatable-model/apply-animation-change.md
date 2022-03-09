//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[AnimatableModel](index.md)/[applyAnimationChange](apply-animation-change.md)

# applyAnimationChange

[androidJvm]\
abstract fun [applyAnimationChange](apply-animation-change.md)(animation: [ModelAnimation](../-model-animation/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Occurs when a [ModelAnimation](../-model-animation/index.md) has received any property changed. Depending on the returned value, the [ModelAnimation](../-model-animation/index.md) will set his isDirty to false or not. You can choose between applying changes on the [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html)[android.view.Choreographer.FrameCallback](https://developer.android.com/reference/kotlin/android/view/Choreographer.FrameCallback.html) or use your own [android.view.Choreographer](https://developer.android.com/reference/kotlin/android/view/Choreographer.html) to handle an update/render update hierarchy. Time position should be applied inside a global [android.view.Choreographer](https://developer.android.com/reference/kotlin/android/view/Choreographer.html) frame callback to ensure that the transformations are applied in a hierarchical order.

#### Return

true is the changes have been applied/handled
