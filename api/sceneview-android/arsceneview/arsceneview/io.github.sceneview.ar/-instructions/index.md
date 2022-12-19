//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[Instructions](index.md)

# Instructions

[androidJvm]\
class [Instructions](index.md)(lifecycle: [ArSceneLifecycle](../-ar-scene-lifecycle/index.md)) : [ArSceneLifecycleObserver](../-ar-scene-lifecycle-observer/index.md)

## Constructors

| | |
|---|---|
| [Instructions](-instructions.md) | [androidJvm]<br>fun [Instructions](-instructions.md)(lifecycle: [ArSceneLifecycle](../-ar-scene-lifecycle/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [onArFrame](on-ar-frame.md) | [androidJvm]<br>open override fun [onArFrame](on-ar-frame.md)(arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) |
| [onArSessionConfigChanged](on-ar-session-config-changed.md) | [androidJvm]<br>open override fun [onArSessionConfigChanged](on-ar-session-config-changed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), config: Config) |
| [onArSessionCreated](../-ar-scene-lifecycle-observer/on-ar-session-created.md) | [androidJvm]<br>open fun [onArSessionCreated](../-ar-scene-lifecycle-observer/on-ar-session-created.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onArSessionFailed](../-ar-scene-lifecycle-observer/on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](../-ar-scene-lifecycle-observer/on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](../-ar-scene-lifecycle-observer/on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](../-ar-scene-lifecycle-observer/on-ar-session-resumed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](../../io.github.sceneview.ar.camera/-ar-camera-stream/index.md#1057561704%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onDestroy](../../io.github.sceneview.ar.camera/-ar-camera-stream/index.md#1057561704%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [augmentedImageInfoEnabled](augmented-image-info-enabled.md) | [androidJvm]<br>var [augmentedImageInfoEnabled](augmented-image-info-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [augmentedImageInfoNode](augmented-image-info-node.md) | [androidJvm]<br>val [augmentedImageInfoNode](augmented-image-info-node.md): [AugmentedImageInfoNode](../../io.github.sceneview.ar.node.infos/-augmented-image-info-node/index.md) |
| [enabled](enabled.md) | [androidJvm]<br>var [enabled](enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [infoNode](info-node.md) | [androidJvm]<br>var [infoNode](info-node.md): Node? = null |
| [searchPlaneInfoEnabled](search-plane-info-enabled.md) | [androidJvm]<br>var [searchPlaneInfoEnabled](search-plane-info-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [searchPlaneInfoNode](search-plane-info-node.md) | [androidJvm]<br>val [searchPlaneInfoNode](search-plane-info-node.md): [SearchPlaneInfoNode](../../io.github.sceneview.ar.node.infos/-search-plane-info-node/index.md) |
| [tapArPlaneInfoEnabled](tap-ar-plane-info-enabled.md) | [androidJvm]<br>var [tapArPlaneInfoEnabled](tap-ar-plane-info-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [tapArPlaneInfoNode](tap-ar-plane-info-node.md) | [androidJvm]<br>val [tapArPlaneInfoNode](tap-ar-plane-info-node.md): [TapArPlaneInfoNode](../../io.github.sceneview.ar.node.infos/-tap-ar-plane-info-node/index.md) |
