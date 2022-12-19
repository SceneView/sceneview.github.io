//[sceneview](../../../../index.md)/[io.github.sceneview](../../index.md)/[SceneView](../index.md)/[FrameCallback](index.md)

# FrameCallback

[androidJvm]\
inner class [FrameCallback](index.md) : [Choreographer.FrameCallback](https://developer.android.com/reference/kotlin/android/view/Choreographer.FrameCallback.html)

## Constructors

| | |
|---|---|
| [FrameCallback](-frame-callback.md) | [androidJvm]<br>fun [FrameCallback](-frame-callback.md)() |

## Functions

| Name | Summary |
|---|---|
| [doFrame](do-frame.md) | [androidJvm]<br>open override fun [doFrame](do-frame.md)(frameTimeNanos: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))<br>Callback that occurs for each display frame. Updates the scene and reposts itself to be called by the choreographer on the next frame. |
