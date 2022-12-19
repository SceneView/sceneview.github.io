//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[setLensProjection](set-lens-projection.md)

# setLensProjection

[androidJvm]\
open fun [setLensProjection](set-lens-projection.md)(focalLength: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aspect: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Sets the projection matrix from the focal length.

## Parameters

androidJvm

| | |
|---|---|
| focalLength | lens's focal length in millimeters. `focalLength` 0 |
| aspect | aspect ratio width/height. `aspect` 0 |
| near | distance in world units from the camera to the near plane. The near plane's position in view space is z = -`near`. Precondition: `near` 0 for Projection.PERSPECTIVE or `near` != `far` for Projection.ORTHO. |
| far | distance in world units from the camera to the far plane. The far plane's position in view space is z = -`far`. Precondition: `far``near` for Projection.PERSPECTIVE or `far` != `near` for Projection.ORTHO. |
