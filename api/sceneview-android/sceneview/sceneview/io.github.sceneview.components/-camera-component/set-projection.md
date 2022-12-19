//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[setProjection](set-projection.md)

# setProjection

[androidJvm]\
open fun [setProjection](set-projection.md)(projection: Camera.Projection, left: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), right: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), bottom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), top: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Sets the projection matrix from a frustum defined by six planes.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.Camera.Projection |  |

## Parameters

androidJvm

| | |
|---|---|
| projection | type of projection to use |
| left | distance in world units from the camera to the left plane, at the near plane. Precondition: `left` != `right` |
| right | distance in world units from the camera to the right plane, at the near plane. Precondition: `left` != `right` |
| bottom | distance in world units from the camera to the bottom plane, at the near plane. Precondition: `bottom` != `top` |
| top | distance in world units from the camera to the top plane, at the near plane. Precondition: `bottom` != `top` |
| near | distance in world units from the camera to the near plane. The near plane's position in view space is z = -`near`. Precondition: `near` 0 for Projection.PERSPECTIVE or `near` != `far` for Projection.ORTHO. |
| far | distance in world units from the camera to the far plane. The far plane's position in view space is z = -`far`. Precondition: `far``near` for Projection.PERSPECTIVE or `far` != `near` for Projection.ORTHO.<br>These parameters are silently modified to meet the preconditions above. |

[androidJvm]\
open fun [setProjection](set-projection.md)(fovInDegrees: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aspect: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), direction: Camera.Fov)

Sets the projection matrix from the field-of-view.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.Camera.Fov |  |

## Parameters

androidJvm

| | |
|---|---|
| fovInDegrees | full field-of-view in degrees. 0 <`fovInDegrees`< 180 |
| aspect | aspect ratio width/height. `aspect` 0 |
| near | distance in world units from the camera to the near plane. The near plane's position in view space is z = -`near`. Precondition: `near` 0 for Projection.PERSPECTIVE or `near` != `far` for Projection.ORTHO. |
| far | distance in world units from the camera to the far plane. The far plane's position in view space is z = -`far`. Precondition: `far``near` for Projection.PERSPECTIVE or `far` != `near` for Projection.ORTHO. |
| direction | direction of the field-of-view parameter.<br>These parameters are silently modified to meet the preconditions above. |
