//[sceneview](../../../../index.md)/[io.github.sceneview](../../index.md)/[SceneView](../index.md)/[CameraGestureListener](index.md)

# CameraGestureListener

[androidJvm]\
inner class [CameraGestureListener](index.md) : [CameraGestureDetector.OnCameraGestureListener](../../../io.github.sceneview.gesture/-camera-gesture-detector/-on-camera-gesture-listener/index.md)

## Constructors

| | |
|---|---|
| [CameraGestureListener](-camera-gesture-listener.md) | [androidJvm]<br>fun [CameraGestureListener](-camera-gesture-listener.md)() |

## Functions

| Name | Summary |
|---|---|
| [onGrabBegin](on-grab-begin.md) | [androidJvm]<br>open override fun [onGrabBegin](on-grab-begin.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), strafe: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>In MAP mode, this starts a panning session. In ORBIT mode, this starts either rotating or strafing. In FREE_FLIGHT mode, this starts a nodal panning session. |
| [onGrabEnd](on-grab-end.md) | [androidJvm]<br>open override fun [onGrabEnd](on-grab-end.md)() |
| [onGrabUpdate](on-grab-update.md) | [androidJvm]<br>open override fun [onGrabUpdate](on-grab-update.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>This is called at least once between [onGrabBegin](on-grab-begin.md) / [onGrabEnd](on-grab-end.md) to dirty the camera. |
| [onScroll](on-scroll.md) | [androidJvm]<br>open override fun [onScroll](on-scroll.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scrollDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>In FREE_FLIGHT mode, adjusts the move speed of the camera. |
