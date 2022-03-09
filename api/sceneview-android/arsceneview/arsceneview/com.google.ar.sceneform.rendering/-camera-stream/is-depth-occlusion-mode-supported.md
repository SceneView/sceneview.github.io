//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CameraStream](index.md)/[isDepthOcclusionModeSupported](is-depth-occlusion-mode-supported.md)

# isDepthOcclusionModeSupported

[androidJvm]\
open fun [isDepthOcclusionModeSupported](is-depth-occlusion-mode-supported.md)(depthOcclusionMode: [CameraStream.DepthOcclusionMode](-depth-occlusion-mode/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks whether the provided DepthOcclusionMode is supported on this device with the selected camera configuration and AR config. The current list of supported devices is documented on the ARCore supported devices page.

#### Return

True if the depth mode has been activated on the AR session config and the provided depth occlusion mode is supported on this device.

## Parameters

androidJvm

| | |
|---|---|
| depthOcclusionMode | The desired depth mode to check. |
