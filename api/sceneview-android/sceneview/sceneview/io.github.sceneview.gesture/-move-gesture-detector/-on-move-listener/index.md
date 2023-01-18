//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[OnMoveListener](index.md)

# OnMoveListener

[androidJvm]\
interface [OnMoveListener](index.md)

###  The listener for receiving notifications when gestures occur

If you want to listen for the different gestures then implement this interface.

An application will receive events in the following order:

- 
   One [onMoveBegin](on-move-begin.md)
- 
   Zero or more [onMove](on-move.md)
- 
   One [onMoveEnd](on-move-end.md)

## Functions

| Name | Summary |
|---|---|
| [onMove](on-move.md) | [androidJvm]<br>abstract fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>abstract fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onMoveEnd](on-move-end.md) | [androidJvm]<br>abstract fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Reported by existing pointers going up. |

## Inheritors

| Name |
|---|
| [SimpleOnMoveListener](../-simple-on-move-listener/index.md) |
