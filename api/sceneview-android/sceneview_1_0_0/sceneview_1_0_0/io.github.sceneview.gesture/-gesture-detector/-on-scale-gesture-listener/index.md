//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[GestureDetector](../index.md)/[OnScaleGestureListener](index.md)

# OnScaleGestureListener

[androidJvm]\
inner class [OnScaleGestureListener](index.md) : [ScaleGestureDetector.SimpleOnScaleListener](../../-scale-gesture-detector/-simple-on-scale-listener/index.md)

## Constructors

| | |
|---|---|
| [OnScaleGestureListener](-on-scale-gesture-listener.md) | [androidJvm]<br>fun [OnScaleGestureListener](-on-scale-gesture-listener.md)() |

## Functions

| Name | Summary |
|---|---|
| [onScale](on-scale.md) | [androidJvm]<br>open override fun [onScale](on-scale.md)(detector: [ScaleGestureDetector](../../-scale-gesture-detector/index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to scaling events for a gesture in progress. Reported by pointer motion |
| [onScaleBegin](on-scale-begin.md) | [androidJvm]<br>open override fun [onScaleBegin](on-scale-begin.md)(detector: [ScaleGestureDetector](../../-scale-gesture-detector/index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to the beginning of a scaling gesture. Reported by new pointers going down |
| [onScaleEnd](on-scale-end.md) | [androidJvm]<br>open override fun [onScaleEnd](on-scale-end.md)(detector: [ScaleGestureDetector](../../-scale-gesture-detector/index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the end of a scale gesture. Reported by existing pointers going up |
