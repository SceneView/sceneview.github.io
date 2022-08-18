//[arsceneview](../../index.md)/[io.github.sceneview.ar](index.md)/[defaultApproximateDistance](default-approximate-distance.md)

# defaultApproximateDistance

[androidJvm]\
const val [defaultApproximateDistance](default-approximate-distance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f

###  Assumed distance in meters from the device camera to the surface on which user will try to

place models

This value affects the apparent scale of objects while the tracking method of the Instant Placement point is SCREENSPACE_WITH_APPROXIMATE_DISTANCE. Values in the 0.2, 2.0 meter range are a good choice for most AR experiences. Use lower values for AR experiences where users are expected to place objects on surfaces close to the camera. Use larger values for experiences where the user will likely be standing and trying to place an object on the ground or floor in front of them.
