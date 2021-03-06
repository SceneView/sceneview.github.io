//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[SceneGestureDetector](../index.md)/[OnSceneGestureListener](index.md)/[onRotate](on-rotate.md)

# onRotate

[androidJvm]\
open override fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../../-rotate-gesture-detector/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Responds to rotating events for a gesture in progress

Reported by pointer motion.

#### Return

Whether or not the detector should consider this event as handled. If an event was not handled, the detector will continue to accumulate movement until an event is handled. This can be useful if an application, for example, only wants to update rotation factors if the change is greater than 0.01.

## Parameters

androidJvm

| | |
|---|---|
| detector | The detector reporting the event - use this to retrieve extended info about event state. |
