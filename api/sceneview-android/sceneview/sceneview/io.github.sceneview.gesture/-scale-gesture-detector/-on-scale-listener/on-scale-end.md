//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[ScaleGestureDetector](../index.md)/[OnScaleListener](index.md)/[onScaleEnd](on-scale-end.md)

# onScaleEnd

[androidJvm]\
abstract fun [onScaleEnd](on-scale-end.md)(detector: [ScaleGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

Responds to the end of a scale gesture. Reported by existing pointers going up

Once a scale has ended, [ScaleGestureDetector.getFocusX](../../../../../sceneview/io.github.sceneview.gesture/-scale-gesture-detector/get-focus-x.md) and [ScaleGestureDetector.getFocusY](../../../../../sceneview/io.github.sceneview.gesture/-scale-gesture-detector/get-focus-y.md) will return focal point of the pointers remaining on the screen.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
