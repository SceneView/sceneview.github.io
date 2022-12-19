//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)

# CameraComponent

[androidJvm]\
interface [CameraComponent](index.md) : [Component](../-component/index.md)

## Functions

| Name | Summary |
|---|---|
| [lookAt](look-at.md) | [androidJvm]<br>open fun [lookAt](look-at.md)(eye: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623), center: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623), up: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623))<br>Sets the camera's model matrix. |
| [setCustomProjection](set-custom-projection.md) | [androidJvm]<br>open fun [setCustomProjection](set-custom-projection.md)(inProjection: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623), inProjectionForCulling: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)? = null, near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets a custom projection matrix. |
| [setExposure](set-exposure.md) | [androidJvm]<br>open fun [setExposure](set-exposure.md)(exposure: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Sets this camera's exposure directly. Calling this method will set the aperture to 1.0, the shutter speed to 1.2 and the sensitivity will be computed to match the requested exposure (for a desired exposure of 1.0, the sensitivity will be set to 100 ISO).<br>[androidJvm]<br>open fun [setExposure](set-exposure.md)(aperture: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), shutterSpeed: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), sensitivity: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Sets this camera's exposure (default is f/16, 1/125s, 100 ISO) |
| [setLensProjection](set-lens-projection.md) | [androidJvm]<br>open fun [setLensProjection](set-lens-projection.md)(focalLength: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aspect: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the projection matrix from the focal length. |
| [setProjection](set-projection.md) | [androidJvm]<br>open fun [setProjection](set-projection.md)(fovInDegrees: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), aspect: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), direction: Camera.Fov)<br>Sets the projection matrix from the field-of-view.<br>[androidJvm]<br>open fun [setProjection](set-projection.md)(projection: Camera.Projection, left: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), right: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), bottom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), top: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), near: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), far: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets the projection matrix from a frustum defined by six planes. |
| [setScaling](set-scaling.md) | [androidJvm]<br>open fun [setScaling](set-scaling.md)(scaling: Float2)<br>Sets an additional matrix that scales the projection matrix. |
| [setShift](set-shift.md) | [androidJvm]<br>open fun [setShift](set-shift.md)(xShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Sets an additional matrix that shifts (translates) the projection matrix. |

## Properties

| Name | Summary |
|---|---|
| [aperture](aperture.md) | [androidJvm]<br>open val [aperture](aperture.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Gets the aperture in f-stops |
| [camera](camera.md) | [androidJvm]<br>open val [camera](camera.md): [FilamentCamera](../index.md#838134813%2FClasslikes%2F-1571379623) |
| [cullingFar](culling-far.md) | [androidJvm]<br>open val [cullingFar](culling-far.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Gets the distance to the far plane |
| [cullingProjectionTransform](culling-projection-transform.md) | [androidJvm]<br>open val [cullingProjectionTransform](culling-projection-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)<br>Retrieves the camera's culling matrix. The culling matrix is the same as the projection matrix, except the far plane is finite. |
| [engine](../-component/engine.md) | [androidJvm]<br>abstract val [engine](../-component/engine.md): Engine |
| [entity](../-component/entity.md) | [androidJvm]<br>abstract val [entity](../-component/entity.md): [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623) |
| [focalLength](focal-length.md) | [androidJvm]<br>open val [focalLength](focal-length.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the focal length in meters |
| [focusDistance](focus-distance.md) | [androidJvm]<br>open var [focusDistance](focus-distance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>The distance from the camera to the focus plane in world units |
| [forwardDirection](forward-direction.md) | [androidJvm]<br>open val [forwardDirection](forward-direction.md): [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)<br>Retrieves the camera forward unit vector in world space, that is a unit vector that points in the direction the camera is looking at. |
| [leftDirection](left-direction.md) | [androidJvm]<br>open val [leftDirection](left-direction.md): [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)<br>Retrieves the camera left unit vector in world space, that is a unit vector that points to the left of the camera. |
| [modelTransform](model-transform.md) | [androidJvm]<br>open var [modelTransform](model-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)<br>The camera's model matrix. |
| [near](near.md) | [androidJvm]<br>open val [near](near.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Gets the distance to the near plane |
| [projectionTransform](projection-transform.md) | [androidJvm]<br>open val [projectionTransform](projection-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)<br>Retrieves the camera's projection matrix. The projection matrix used for rendering always has its far plane set to infinity. This is why it may differ from the matrix set through setProjection() or setLensProjection(). |
| [scaling](scaling.md) | [androidJvm]<br>open val [scaling](scaling.md): Float4<br>Returns the scaling amount used to scale the projection matrix. |
| [sensitivity](sensitivity.md) | [androidJvm]<br>open val [sensitivity](sensitivity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Gets the sensitivity in ISO |
| [shutterSpeed](shutter-speed.md) | [androidJvm]<br>open val [shutterSpeed](shutter-speed.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Gets the shutter speed in seconds |
| [upDirection](up-direction.md) | [androidJvm]<br>open val [upDirection](up-direction.md): [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)<br>Retrieves the camera up unit vector in world space, that is a unit vector that points up with respect to the camera. |
| [viewTransform](view-transform.md) | [androidJvm]<br>open val [viewTransform](view-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)<br>Retrieves the camera's view matrix. The view matrix is the inverse of the model matrix. |

## Inheritors

| Name |
|---|
| [CameraNode](../../io.github.sceneview.nodes/-camera-node/index.md) |
| [CameraNode](../../io.github.sceneview.nodes/-model-node/-camera-node/index.md) |
