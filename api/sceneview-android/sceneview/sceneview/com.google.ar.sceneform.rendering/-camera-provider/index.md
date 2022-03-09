//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CameraProvider](index.md)

# CameraProvider

[androidJvm]\
interface [CameraProvider](index.md) : [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)

Required interface for a virtual camera.

## Functions

| Name | Summary |
|---|---|
| [getFarClipPlane](get-far-clip-plane.md) | [androidJvm]<br>abstract fun [getFarClipPlane](get-far-clip-plane.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getNearClipPlane](get-near-clip-plane.md) | [androidJvm]<br>abstract fun [getNearClipPlane](get-near-clip-plane.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getProjectionMatrix](get-projection-matrix.md) | [androidJvm]<br>abstract fun [getProjectionMatrix](get-projection-matrix.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md) |
| [getTransformationMatrix](../../com.google.ar.sceneform.common/-transform-provider/get-transformation-matrix.md) | [androidJvm]<br>abstract fun [getTransformationMatrix](../../com.google.ar.sceneform.common/-transform-provider/get-transformation-matrix.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md) |
| [getViewMatrix](get-view-matrix.md) | [androidJvm]<br>abstract fun [getViewMatrix](get-view-matrix.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md) |
| [isRendered](is-rendered.md) | [androidJvm]<br>abstract fun [isRendered](is-rendered.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [Camera](../../com.google.ar.sceneform/-camera/index.md) |
