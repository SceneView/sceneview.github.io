//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.scene](index.md)

# Package io.github.sceneview.scene

## Types

| Name | Summary |
|---|---|
| [ClipSpacePosition](index.md#1417114357%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [ClipSpacePosition](index.md#1417114357%2FClasslikes%2F-602047187) = [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun IndirectLight.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): IndirectLight<br>fun Skybox.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): Skybox |
| [clipSpaceToViewSpace](clip-space-to-view-space.md) | [androidJvm]<br>fun Camera.[clipSpaceToViewSpace](clip-space-to-view-space.md)(clipSpacePosition: [ClipSpacePosition](index.md#1417114357%2FClasslikes%2F-602047187)): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) |
| [createCamera](create-camera.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[createCamera](create-camera.md)(entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187) = EntityManager.get().create()): Camera<br>Creates and adds a Camera component to a given `entity` |
| [destroyCamera](destroy-camera.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyCamera](destroy-camera.md)(camera: Camera)<br>Destroys the Camera component associated with the given entity |
| [destroyIndirectLight](destroy-indirect-light.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyIndirectLight](destroy-indirect-light.md)(indirectLight: IndirectLight) |
| [destroySkybox](destroy-skybox.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroySkybox](destroy-skybox.md)(skybox: Skybox) |
| [getLookAt](get-look-at.md) | [androidJvm]<br>fun Manipulator.[getLookAt](get-look-at.md)(): [LookAt](../io.github.sceneview.math/-look-at/index.md)<br>The current orthonormal basis. This is usually called once per frame |
| [illuminance](illuminance.md) | [androidJvm]<br>fun Camera.[illuminance](illuminance.md)(ev100: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [lookAt](look-at.md) | [androidJvm]<br>fun Camera.[lookAt](look-at.md)(eye: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187), center: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187), up: [Direction](../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-602047187))<br>Sets the camera's model matrix. |
| [luminance](luminance.md) | [androidJvm]<br>fun Camera.[luminance](luminance.md)(ev100: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [setCustomProjection](set-custom-projection.md) | [androidJvm]<br>fun Camera.[setCustomProjection](set-custom-projection.md)(transform: [Transform](../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187), near: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), far: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [targetPosition](target-position.md) | [androidJvm]<br>fun Manipulator.Builder.[targetPosition](target-position.md)(position: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): Manipulator.Builder<br>Sets world-space position of interest, which defaults to (0,0,0) |
| [viewSpaceToClipSpace](view-space-to-clip-space.md) | [androidJvm]<br>fun Camera.[viewSpaceToClipSpace](view-space-to-clip-space.md)(viewSpacePosition: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): [ClipSpacePosition](index.md#1417114357%2FClasslikes%2F-602047187) |
| [viewSpaceToWorld](view-space-to-world.md) | [androidJvm]<br>fun Camera.[viewSpaceToWorld](view-space-to-world.md)(viewSpacePosition: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) |
| [worldToViewSpace](world-to-view-space.md) | [androidJvm]<br>fun Camera.[worldToViewSpace](world-to-view-space.md)(worldPosition: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) |

## Properties

| Name | Summary |
|---|---|
| [ev100](ev100.md) | [androidJvm]<br>val Camera.[ev100](ev100.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Computes the camera's EV100 from exposure settings |
| [exposureFactor](exposure-factor.md) | [androidJvm]<br>val Camera.[exposureFactor](exposure-factor.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Computes the exposure normalization factor from the camera's EV100 |
| [illuminance](illuminance.md) | [androidJvm]<br>val Camera.[illuminance](illuminance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [luminance](luminance.md) | [androidJvm]<br>val Camera.[luminance](luminance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [modelMatrix](model-matrix.md) | [androidJvm]<br>var Camera.[modelMatrix](model-matrix.md): [Transform](../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187)<br>The camera's model matrix. The model matrix encodes the camera position and orientation, or pose |
| [projectionMatrix](projection-matrix.md) | [androidJvm]<br>val Camera.[projectionMatrix](projection-matrix.md): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md)<br>The camera's projection matrix |
| [viewMatrix](view-matrix.md) | [androidJvm]<br>val Camera.[viewMatrix](view-matrix.md): [Mat4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-mat4/index.md)<br>The camera's view matrix. The view matrix is the inverse of the model matrix |
