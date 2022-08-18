//[sceneview](../../../../index.md)/[io.github.sceneview.gesture](../../index.md)/[CameraGestureDetector](../index.md)/[OnCameraGestureListener](index.md)

# OnCameraGestureListener

[androidJvm]\
interface [OnCameraGestureListener](index.md)

## Functions

| Name | Summary |
|---|---|
| [onGrabBegin](on-grab-begin.md) | [androidJvm]<br>abstract fun [onGrabBegin](on-grab-begin.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), strafe: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>In MAP mode, this starts a panning session. In ORBIT mode, this starts either rotating or strafing. In FREE_FLIGHT mode, this starts a nodal panning session. |
| [onGrabEnd](on-grab-end.md) | [androidJvm]<br>abstract fun [onGrabEnd](on-grab-end.md)() |
| [onGrabUpdate](on-grab-update.md) | [androidJvm]<br>abstract fun [onGrabUpdate](on-grab-update.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This is called at least once between [onGrabBegin](on-grab-begin.md) / [onGrabEnd](on-grab-end.md) to dirty the camera. |
| [onScroll](on-scroll.md) | [androidJvm]<br>abstract fun [onScroll](on-scroll.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scrollDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>In FREE_FLIGHT mode, adjusts the move speed of the camera. |

## Inheritors

| Name |
|---|
| [CameraGestureListener](../../../io.github.sceneview/-scene-view/-camera-gesture-listener/index.md) |
| [SimpleOnCameraGestureListener](../-simple-on-camera-gesture-listener/index.md) |
