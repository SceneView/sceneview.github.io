//[sceneview](../../../../index.md)/[io.github.sceneview](../../index.md)/[SceneView](../index.md)/[CameraGestureListener](index.md)/[onScroll](on-scroll.md)

# onScroll

[androidJvm]\
open override fun [onScroll](on-scroll.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), scrollDelta: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

###  In MAP and ORBIT modes, dollys the camera along the viewing direction

In FREE_FLIGHT mode, adjusts the move speed of the camera.

## Parameters

androidJvm

| | |
|---|---|
| x | X-coordinate for point of interest in viewport space, ignored in FREE_FLIGHT mode |
| y | Y-coordinate for point of interest in viewport space, ignored in FREE_FLIGHT mode |
| scrollDelta | In MAP and ORBIT modes, negative means "zoom in", positive means "zoom out" In FREE_FLIGHT mode, negative means "slower", positive means "faster" |
