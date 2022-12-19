//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[ScaleGestureDetector](../index.md)/[SimpleOnScaleListener](index.md)

# SimpleOnScaleListener

[androidJvm]\
interface [SimpleOnScaleListener](index.md) : [ScaleGestureDetector.OnScaleListener](../-on-scale-listener/index.md)

A convenience class to extend when you only want to listen for a subset of  scale-related events

This implements all methods in [OnScaleListener](../-on-scale-listener/index.md) but does nothing. [OnScaleListener.onScale](../-on-scale-listener/on-scale.md) returns `false` so that a subclass can retrieve the accumulated scale factor in an overridden [OnScaleListener.onScaleEnd](../-on-scale-listener/on-scale-end.md). [OnScaleListener.onScaleBegin](../-on-scale-listener/on-scale-begin.md) returns `true`.

## Functions

| Name | Summary |
|---|---|
| [onScale](on-scale.md) | [androidJvm]<br>open override fun [onScale](on-scale.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to scaling events for a gesture in progress. Reported by pointer motion |
| [onScaleBegin](on-scale-begin.md) | [androidJvm]<br>open override fun [onScaleBegin](on-scale-begin.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to the beginning of a scaling gesture. Reported by new pointers going down |
| [onScaleEnd](on-scale-end.md) | [androidJvm]<br>open override fun [onScaleEnd](on-scale-end.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the end of a scale gesture. Reported by existing pointers going up |

## Inheritors

| Name |
|---|
| [OnScaleGestureListener](../../-gesture-detector/-on-scale-gesture-listener/index.md) |
