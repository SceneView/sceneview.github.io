//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[SimpleOnMoveListener](index.md)

# SimpleOnMoveListener

[androidJvm]\
interface [SimpleOnMoveListener](index.md) : [MoveGestureDetector.OnMoveListener](../-on-move-listener/index.md)

A convenience class to extend when you only want to listen for a subset of move-related events

This implements all methods in [OnMoveListener](../-on-move-listener/index.md) but does nothing. [OnMoveListener.onMove](../-on-move-listener/on-move.md) returns `false` so that a subclass can retrieve the accumulated moving factor in an overridden [OnMoveListener.onMoveEnd](../-on-move-listener/on-move-end.md). [OnMoveListener.onMoveBegin](../-on-move-listener/on-move-begin.md) returns `true`.

## Functions

| Name | Summary |
|---|---|
| [onMove](on-move.md) | [androidJvm]<br>open override fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to moving events for a gesture in progress |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>open override fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the beginning of a moving gesture |
| [onMoveEnd](on-move-end.md) | [androidJvm]<br>open override fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Responds to the end of a move gesture |

## Inheritors

| Name |
|---|
| [OnMoveGestureListener](../../-gesture-detector/-on-move-gesture-listener/index.md) |
