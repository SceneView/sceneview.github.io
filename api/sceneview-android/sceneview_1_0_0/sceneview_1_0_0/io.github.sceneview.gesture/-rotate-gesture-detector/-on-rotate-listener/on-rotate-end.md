//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[RotateGestureDetector](../index.md)/[OnRotateListener](index.md)/[onRotateEnd](on-rotate-end.md)

# onRotateEnd

[androidJvm]\
abstract fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

Responds to the end of a scale gesture

Reported by existing pointers going up.

Once a scale has ended, [focusX](../focus-x.md) and [focusY](../focus-y.md) will return focal point of the pointers remaining on the screen.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
