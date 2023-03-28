//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[SimpleOnMoveListener](index.md)/[onMove](on-move.md)

# onMove

[androidJvm]\
open override fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

Responds to moving events for a gesture in progress

Reported by pointer motion.

#### Return

Whether or not the detector should consider this event as handled. If an event was not handled, the detector will continue to accumulate movement until an event is handled. This can be useful if an application, for example, only wants to update rotation factors if the change is greater than 0.01.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
