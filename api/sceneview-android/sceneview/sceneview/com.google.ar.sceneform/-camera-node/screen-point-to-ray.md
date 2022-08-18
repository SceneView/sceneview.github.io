//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[CameraNode](index.md)/[screenPointToRay](screen-point-to-ray.md)

# screenPointToRay

[androidJvm]\
open fun [screenPointToRay](screen-point-to-ray.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Ray](../../com.google.ar.sceneform.collision/-ray/index.md)

Calculates a ray in world space going from the near-plane of the camera and going through a point in screen space. Screen space is in Android device screen coordinates: TopLeft = (0, 0) BottomRight = (Screen Width, Screen Height) The device coordinate space is unaffected by the orientation of the device.

## Parameters

androidJvm

| | |
|---|---|
| x | X position in device screen coordinates. |
| y | Y position in device screen coordinates. |
