//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[RotateGestureDetector](../index.md)/[OnRotateGestureListener](index.md)/[onRotateBegin](on-rotate-begin.md)

# onRotateBegin

[androidJvm]\
abstract fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Responds to the beginning of a scaling gesture

Reported by new pointers going down.

#### Return

Whether or not the detector should continue recognizing this gesture. For example, if a gesture is beginning with a focal point outside of a region where it makes sense, onRotateBegin() may return false to ignore the rest of the gesture.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
