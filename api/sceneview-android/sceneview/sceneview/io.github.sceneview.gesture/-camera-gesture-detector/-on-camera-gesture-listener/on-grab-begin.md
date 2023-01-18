//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[CameraGestureDetector](../index.md)/[OnCameraGestureListener](index.md)/[onGrabBegin](on-grab-begin.md)

# onGrabBegin

[androidJvm]\
abstract fun [onGrabBegin](on-grab-begin.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), strafe: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

###  Start of a grabbing session (i.e. the user is dragging around in the viewport).

In MAP mode, this starts a panning session. In ORBIT mode, this starts either rotating or strafing. In FREE_FLIGHT mode, this starts a nodal panning session.

## Parameters

androidJvm

| | |
|---|---|
| x | X-coordinate for point of interest in viewport space |
| y | Y-coordinate for point of interest in viewport space |
| strafe | ORBIT mode only; if true, starts a translation rather than a rotation |
