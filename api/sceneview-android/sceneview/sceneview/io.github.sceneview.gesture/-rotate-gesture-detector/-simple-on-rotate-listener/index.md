//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[RotateGestureDetector](../index.md)/[SimpleOnRotateListener](index.md)

# SimpleOnRotateListener

[androidJvm]\
interface [SimpleOnRotateListener](index.md) : [RotateGestureDetector.OnRotateListener](../-on-rotate-listener/index.md)

###  A convenience class to extend when you only want to listen for a subset of

rotation-related events

This implements all methods in [OnRotateListener](../-on-rotate-listener/index.md) but does nothing. [OnRotateListener.onRotate](../-on-rotate-listener/on-rotate.md) returns `false` so that a subclass can retrieve the accumulated rotation factor in an overridden [OnRotateListener.onRotateEnd](../-on-rotate-listener/on-rotate-end.md). [OnRotateListener.onRotateBegin](../-on-rotate-listener/on-rotate-begin.md) returns `true`.

## Functions

| Name | Summary |
|---|---|
| [onRotate](on-rotate.md) | [androidJvm]<br>open override fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>open override fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onRotateEnd](on-rotate-end.md) | [androidJvm]<br>open override fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Reported by existing pointers going up. |
