//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[SimpleOnMoveListener](index.md)/[onMoveBegin](on-move-begin.md)

# onMoveBegin

[androidJvm]\
open override fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

Responds to the beginning of a moving gesture

Reported by new pointers going down.

#### Return

Whether or not the detector should continue recognizing this gesture. For example, if a gesture is beginning with a focal point outside of a region where it makes sense, onRotateBegin() may return false to ignore the rest of the gesture.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
