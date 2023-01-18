//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[MoveGestureDetector](../index.md)/[OnMoveListener](index.md)/[onMove](on-move.md)

# onMove

[androidJvm]\
abstract fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md), e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Responds to moving events for a gesture in progress

Reported by pointer motion.

#### Return

Whether or not the detector should consider this event as handled. If an event was not handled, the detector will continue to accumulate movement until an event is handled. This can be useful if an application, for example, only wants to update rotation factors if the change is greater than 0.01.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
