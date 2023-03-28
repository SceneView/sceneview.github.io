//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[setCustomProjection](set-custom-projection.md)

# setCustomProjection

[androidJvm]\
open fun [setCustomProjection](set-custom-projection.md)(inProjection: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187), inProjectionForCulling: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187)? = null, near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Sets a custom projection matrix.

The projection matrices must define an NDC system that must match the OpenGL convention, that is all 3 axis are mapped to -1, 1.

## Parameters

androidJvm

| | |
|---|---|
| inProjection | custom projection matrix for rendering. |
| inProjectionForCulling | custom projection matrix for culling. |
| near | distance in world units from the camera to the near plane. The near plane's position in view space is z = -`near`. Precondition: `near` 0 for Projection.PERSPECTIVE or `near` != `far` for Projection.ORTHO. |
| far | distance in world units from the camera to the far plane. The far plane's position in view space is z = -`far`. Precondition: `far``near` for Projection.PERSPECTIVE or `far` != `near` for Projection.ORTHO. |
