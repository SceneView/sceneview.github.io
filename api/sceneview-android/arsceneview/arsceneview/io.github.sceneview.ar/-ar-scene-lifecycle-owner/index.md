//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneLifecycleOwner](index.md)

# ArSceneLifecycleOwner

[androidJvm]\
interface [ArSceneLifecycleOwner](index.md) : [SceneLifecycleOwner](../../../../sceneview/sceneview/io.github.sceneview/-scene-lifecycle-owner/index.md)

###  A SurfaceView that integrates with ARCore and renders a scene.

## Functions

| Name | Summary |
|---|---|
| [getLifecycle](index.md#1810192813%2FFunctions%2F-58641720) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>abstract fun [getLifecycle](index.md#1810192813%2FFunctions%2F-58641720)(): [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html) |

## Properties

| Name | Summary |
|---|---|
| [arCore](ar-core.md) | [androidJvm]<br>abstract val [arCore](ar-core.md): [ARCore](../-a-r-core/index.md) |
| [arSession](ar-session.md) | [androidJvm]<br>open val [arSession](ar-session.md): [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)? |
| [arSessionConfig](ar-session-config.md) | [androidJvm]<br>open val [arSessionConfig](ar-session-config.md): Config? |

## Inheritors

| Name |
|---|
| [ArSceneView](../-ar-scene-view/index.md) |
