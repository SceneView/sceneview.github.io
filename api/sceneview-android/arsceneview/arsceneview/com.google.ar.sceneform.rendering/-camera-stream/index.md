//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CameraStream](index.md)

# CameraStream

[androidJvm]\
open class [CameraStream](index.md)

Displays the Camera stream using Filament.

## Constructors

| | |
|---|---|
| [CameraStream](-camera-stream.md) | [androidJvm]<br>open fun [CameraStream](-camera-stream.md)(cameraTextureId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), renderer: [Renderer](../../../../arsceneview/com.google.ar.sceneform.rendering/-renderer/index.md)) |

## Types

| Name | Summary |
|---|---|
| [DepthMode](-depth-mode/index.md) | [androidJvm]<br>enum [DepthMode](-depth-mode/index.md)<br>The DepthMode Enum is used to reflect the Session configuration for the DepthMode to decide if the occlusion material should be set and if frame.acquireDepthImage() or frame.acquireRawDepthImage() should be called to get the input data for the depth texture. |
| [DepthOcclusionMode](-depth-occlusion-mode/index.md) | [androidJvm]<br>enum [DepthOcclusionMode](-depth-occlusion-mode/index.md)<br>Independent from the Session configuration, the user can decide with the DeptModeUsage which com.google.android.filament.Material should be set to the CameraStream renderable. |

## Functions

| Name | Summary |
|---|---|
| [checkIfDepthIsEnabled](check-if-depth-is-enabled.md) | [androidJvm]<br>open fun [checkIfDepthIsEnabled](check-if-depth-is-enabled.md)(session: Session, config: Config)<br>The Session holds the information if the DepthMode is configured or not. |
| [getRenderPriority](get-render-priority.md) | [androidJvm]<br>open fun [getRenderPriority](get-render-priority.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializeTexture](initialize-texture.md) | [androidJvm]<br>open fun [initializeTexture](initialize-texture.md)(arCamera: Camera) |
| [isDepthOcclusionModeSupported](is-depth-occlusion-mode-supported.md) | [androidJvm]<br>open fun [isDepthOcclusionModeSupported](is-depth-occlusion-mode-supported.md)(depthOcclusionMode: [CameraStream.DepthOcclusionMode](-depth-occlusion-mode/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether the provided DepthOcclusionMode is supported on this device with the selected camera configuration and AR config. |
| [recalculateCameraUvs](recalculate-camera-uvs.md) | [androidJvm]<br>open fun [recalculateCameraUvs](recalculate-camera-uvs.md)(frame: Frame) |
| [recalculateOcclusion](recalculate-occlusion.md) | [androidJvm]<br>open fun [recalculateOcclusion](recalculate-occlusion.md)(depthImage: [Image](https://developer.android.com/reference/kotlin/android/media/Image.html))<br>     Update the DepthTexture. |
| [setRenderPriority](set-render-priority.md) | [androidJvm]<br>open fun [setRenderPriority](set-render-priority.md)(priority: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [cameraStreamRenderable](camera-stream-renderable.md) | [androidJvm]<br>open val [cameraStreamRenderable](camera-stream-renderable.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [depthMode](depth-mode.md) | [androidJvm]<br>private open val [depthMode](depth-mode.md): [CameraStream.DepthMode](-depth-mode/index.md)<br>By default the depthMode is set to NO_DEPTH |
| [depthOcclusionMode](depth-occlusion-mode.md) | [androidJvm]<br>private open var [depthOcclusionMode](depth-occlusion-mode.md): [CameraStream.DepthOcclusionMode](-depth-occlusion-mode/index.md)<br>By default the depthOcclusionMode ist set to DEPTH_OCCLUSION_DISABLED |
| [isTextureInitialized](is-texture-initialized.md) | [androidJvm]<br>private open val [isTextureInitialized](is-texture-initialized.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [MATERIAL_CAMERA_TEXTURE](-m-a-t-e-r-i-a-l_-c-a-m-e-r-a_-t-e-x-t-u-r-e.md) | [androidJvm]<br>val [MATERIAL_CAMERA_TEXTURE](-m-a-t-e-r-i-a-l_-c-a-m-e-r-a_-t-e-x-t-u-r-e.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [MATERIAL_DEPTH_TEXTURE](-m-a-t-e-r-i-a-l_-d-e-p-t-h_-t-e-x-t-u-r-e.md) | [androidJvm]<br>val [MATERIAL_DEPTH_TEXTURE](-m-a-t-e-r-i-a-l_-d-e-p-t-h_-t-e-x-t-u-r-e.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
