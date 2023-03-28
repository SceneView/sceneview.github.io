//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[projectionTransform](projection-transform.md)

# projectionTransform

[androidJvm]\
open val [projectionTransform](projection-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187)

Retrieves the camera's projection matrix. The projection matrix used for rendering always has its far plane set to infinity. This is why it may differ from the matrix set through setProjection() or setLensProjection().

Transform containing the camera's projection as a column-major matrix.
