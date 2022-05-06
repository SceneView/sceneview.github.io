//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneLifecycleObserver](index.md)

# ArSceneLifecycleObserver

[androidJvm]\
interface [ArSceneLifecycleObserver](index.md) : [SceneLifecycleObserver](../../../../sceneview/sceneview/io.github.sceneview/-scene-lifecycle-observer/index.md)

## Functions

| Name | Summary |
|---|---|
| [onArFrame](on-ar-frame.md) | [androidJvm]<br>open fun [onArFrame](on-ar-frame.md)(arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) |
| [onArSessionConfigChanged](on-ar-session-config-changed.md) | [androidJvm]<br>open fun [onArSessionConfigChanged](on-ar-session-config-changed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), config: Config) |
| [onArSessionCreated](on-ar-session-created.md) | [androidJvm]<br>open fun [onArSessionCreated](on-ar-session-created.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onArSessionFailed](on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](on-ar-session-resumed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](../../io.github.sceneview.ar.camera/-ar-camera-stream/index.md#1057561704%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onDestroy](../../io.github.sceneview.ar.camera/-ar-camera-stream/index.md#1057561704%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Inheritors

| Name |
|---|
| [ARCore](../-a-r-core/index.md) |
| [ArSceneView](../-ar-scene-view/index.md) |
| [Instructions](../-instructions/index.md) |
| [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md) |
| [LightEstimation](../../io.github.sceneview.ar.arcore/-light-estimation/index.md) |
| [ArCameraStream](../../io.github.sceneview.ar.camera/-ar-camera-stream/index.md) |
| [ArNode](../../io.github.sceneview.ar.node/-ar-node/index.md) |
| [SearchPlaneInfoNode](../../io.github.sceneview.ar.node.infos/-search-plane-info-node/index.md) |
| [PlaneRenderer](../../io.github.sceneview.ar.scene/-plane-renderer/index.md) |
