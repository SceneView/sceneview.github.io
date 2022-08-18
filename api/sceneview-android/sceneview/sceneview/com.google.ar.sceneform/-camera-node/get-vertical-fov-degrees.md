//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[CameraNode](index.md)/[getVerticalFovDegrees](get-vertical-fov-degrees.md)

# getVerticalFovDegrees

[androidJvm]\
open fun [getVerticalFovDegrees](get-vertical-fov-degrees.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

Gets the vertical field of view for the camera. 

If this is an AR camera, then it is calculated based on the camera information from ARCore and can vary between device. It can't be calculated until the first frame after the ARCore session is resumed, in which case an IllegalStateException is thrown. 

Otherwise, this will return the value set by [setVerticalFovDegrees](set-vertical-fov-degrees.md), with a default of 90 degrees.

## Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://developer.android.com/reference/kotlin/java/lang/IllegalStateException.html) | if called before the first frame after ARCore is resumed |
