//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[ScaleGestureDetector](../index.md)/[OnScaleListener](index.md)

# OnScaleListener

[androidJvm]\
interface [OnScaleListener](index.md)

The listener for receiving notifications when gestures occur

If you want to listen for all the different gestures then implement this interface.

An application will receive events in the following order:

- 
   One [onScaleBegin](on-scale-begin.md)
- 
   Zero or more [onScale](on-scale.md)
- 
   One [onScaleEnd](on-scale-end.md)

## Functions

| Name | Summary |
|---|---|
| [onScale](on-scale.md) | [androidJvm]<br>abstract fun [onScale](on-scale.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to scaling events for a gesture in progress. Reported by pointer motion |
| [onScaleBegin](on-scale-begin.md) | [androidJvm]<br>abstract fun [onScaleBegin](on-scale-begin.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to the beginning of a scaling gesture. Reported by new pointers going down |
| [onScaleEnd](on-scale-end.md) | [androidJvm]<br>abstract fun [onScaleEnd](on-scale-end.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the end of a scale gesture. Reported by existing pointers going up |

## Inheritors

| Name |
|---|
| [SimpleOnScaleListener](../-simple-on-scale-listener/index.md) |
