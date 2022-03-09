//[arsceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[CameraStream](../index.md)/[DepthMode](index.md)

# DepthMode

[androidJvm]\
enum [DepthMode](index.md)

The DepthMode Enum is used to reflect the Session configuration for the DepthMode to decide if the occlusion material should be set and if frame.acquireDepthImage() or frame.acquireRawDepthImage() should be called to get the input data for the depth texture.

## Entries

| | |
|---|---|
| [NO_DEPTH](-n-o_-d-e-p-t-h/index.md) | [androidJvm]<br>[NO_DEPTH](-n-o_-d-e-p-t-h/index.md) |
| [DEPTH](-d-e-p-t-h/index.md) | [androidJvm]<br>[DEPTH](-d-e-p-t-h/index.md)<br>The Session is configured to use the DepthMode AUTOMATIC |
| [RAW_DEPTH](-r-a-w_-d-e-p-t-h/index.md) | [androidJvm]<br>[RAW_DEPTH](-r-a-w_-d-e-p-t-h/index.md)<br>The Session is configured to use the DepthMode RAW_DEPTH_ONLY |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [CameraStream.DepthMode](index.md) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[CameraStream.DepthMode](index.md)&gt; |
