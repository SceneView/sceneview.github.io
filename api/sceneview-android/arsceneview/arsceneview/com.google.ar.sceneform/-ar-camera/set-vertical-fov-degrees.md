//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[ArCamera](index.md)/[setVerticalFovDegrees](set-vertical-fov-degrees.md)

# setVerticalFovDegrees

[androidJvm]\
open fun [setVerticalFovDegrees](set-vertical-fov-degrees.md)(verticalFov: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Sets the vertical field of view for the non-ar camera in degrees. If this is an AR camera, then the fov comes from ARCore and cannot be set so an exception is thrown. The default is 90 degrees.

## Throws

| | |
|---|---|
| [java.lang.UnsupportedOperationException](https://developer.android.com/reference/kotlin/java/lang/UnsupportedOperationException.html) | if this is an AR camera |
