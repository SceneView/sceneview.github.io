//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[MoveGestureDetector](../index.md)/[OnMoveGestureListener](index.md)/[onMoveBegin](on-move-begin.md)

# onMoveBegin

[androidJvm]\
abstract fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Responds to the beginning of a moving gesture

Reported by new pointers going down.

#### Return

Whether or not the detector should continue recognizing this gesture. For example, if a gesture is beginning with a focal point outside of a region where it makes sense, onRotateBegin() may return false to ignore the rest of the gesture.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
