//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[RotateGestureDetector](../index.md)/[OnRotateListener](index.md)

# OnRotateListener

[androidJvm]\
interface [OnRotateListener](index.md)

The listener for receiving notifications when gestures occur

If you want to listen for the different gestures then implement this interface.

An application will receive events in the following order:

- 
   One [onRotateBegin](on-rotate-begin.md)
- 
   Zero or more [onRotate](on-rotate.md)
- 
   One [onRotateEnd](on-rotate-end.md)

## Functions

| Name | Summary |
|---|---|
| [onRotate](on-rotate.md) | [androidJvm]<br>abstract fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to rotating events for a gesture in progress |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>abstract fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Responds to the beginning of a scaling gesture |
| [onRotateEnd](on-rotate-end.md) | [androidJvm]<br>abstract fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the end of a scale gesture |

## Inheritors

| Name |
|---|
| [SimpleOnRotateListener](../-simple-on-rotate-listener/index.md) |
