//[arsceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[CameraStream](../index.md)/[DepthOcclusionMode](index.md)

# DepthOcclusionMode

[androidJvm]\
enum [DepthOcclusionMode](index.md)

Independent from the Session configuration, the user can decide with the DeptModeUsage which com.google.android.filament.Material should be set to the CameraStream renderable.

## Entries

| | |
|---|---|
| [DEPTH_OCCLUSION_ENABLED](-d-e-p-t-h_-o-c-c-l-u-s-i-o-n_-e-n-a-b-l-e-d/index.md) | [androidJvm]<br>[DEPTH_OCCLUSION_ENABLED](-d-e-p-t-h_-o-c-c-l-u-s-i-o-n_-e-n-a-b-l-e-d/index.md)<br>Set the occlusion material. If the Session is not configured properly the standard camera material is used. Valid Session configuration for the DepthMode are AUTOMATIC and RAW_DEPTH_ONLY. |
| [DEPTH_OCCLUSION_DISABLED](-d-e-p-t-h_-o-c-c-l-u-s-i-o-n_-d-i-s-a-b-l-e-d/index.md) | [androidJvm]<br>[DEPTH_OCCLUSION_DISABLED](-d-e-p-t-h_-o-c-c-l-u-s-i-o-n_-d-i-s-a-b-l-e-d/index.md) |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [CameraStream.DepthOcclusionMode](index.md) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[CameraStream.DepthOcclusionMode](index.md)&gt; |
