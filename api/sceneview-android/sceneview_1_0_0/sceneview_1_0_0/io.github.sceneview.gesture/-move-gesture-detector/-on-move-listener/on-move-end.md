//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[OnMoveListener](index.md)/[onMoveEnd](on-move-end.md)

# onMoveEnd

[androidJvm]\
abstract fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

Responds to the end of a move gesture

Reported by existing pointers going up.

Once a scale has ended, focusX and focusY will return focal point of the pointers remaining on the screen.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
