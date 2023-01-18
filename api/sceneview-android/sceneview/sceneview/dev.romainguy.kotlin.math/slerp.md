//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[slerp](slerp.md)

# slerp

[androidJvm]\
fun [slerp](slerp.md)(a: [Quaternion](-quaternion/index.md), b: [Quaternion](-quaternion/index.md), t: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), dotThreshold: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.9995f): [Quaternion](-quaternion/index.md)

Spherical linear interpolation between two given orientations

If t is 0 this returns a. As t approaches 1 slerp may approach either b or -b (whichever is closest to a) If t is above 1 or below 0 the result will be extrapolated.

#### Return

Interpolated value between the two floats

## Parameters

androidJvm

| | |
|---|---|
| a | The beginning value |
| b | The ending value |
| t | The ratio between the two floats |
| dotThreshold | If the quaternion dot product is greater than this value (i.e. the quaternions are very close to each other), then the quaternions are linearly interpolated instead of spherically interpolated. |
