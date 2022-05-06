//[arsceneview](../../../index.md)/[io.github.sceneview.ar.scene](../index.md)/[PlaneRenderer](index.md)

# PlaneRenderer

[androidJvm]\
class [PlaneRenderer](index.md)(lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md)) : [ArSceneLifecycleObserver](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md)

Control rendering of ARCore planes.

Used to visualize detected planes and to control whether Renderables cast shadows on them.

## Constructors

| | |
|---|---|
| [PlaneRenderer](-plane-renderer.md) | [androidJvm]<br>fun [PlaneRenderer](-plane-renderer.md)(lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |
| [PlaneRendererMode](-plane-renderer-mode/index.md) | [androidJvm]<br>enum [PlaneRendererMode](-plane-renderer-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PlaneRenderer.PlaneRendererMode](-plane-renderer-mode/index.md)&gt; <br>Use this enum to configure the Plane Rendering. |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [onArFrame](on-ar-frame.md) | [androidJvm]<br>open override fun [onArFrame](on-ar-frame.md)(arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) |
| [onArSessionConfigChanged](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-config-changed.md) | [androidJvm]<br>open fun [onArSessionConfigChanged](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-config-changed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), config: Config) |
| [onArSessionCreated](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-created.md) | [androidJvm]<br>open fun [onArSessionCreated](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-created.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onCreate](index.md#139941652%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onCreate](index.md#139941652%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](on-destroy.md) | [androidJvm]<br>open override fun [onDestroy](on-destroy.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](index.md#-1807945979%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onResume](index.md#-1807945979%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [isEnabled](is-enabled.md) | [androidJvm]<br>var [isEnabled](is-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [isShadowReceiver](is-shadow-receiver.md) | [androidJvm]<br>var [isShadowReceiver](is-shadow-receiver.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>If false - no planes receive shadows, regardless of the per-plane setting. |
| [isVisible](is-visible.md) | [androidJvm]<br>var [isVisible](is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>If false - no planes are drawn. Note that shadow visibility is independent of plane visibility. |
| [materialInstance](material-instance.md) | [androidJvm]<br>var [materialInstance](material-instance.md): MaterialInstance? = null<br>Default material instance used to render the planes. |
| [planeRendererMode](plane-renderer-mode.md) | [androidJvm]<br>var [planeRendererMode](plane-renderer-mode.md): [PlaneRenderer.PlaneRendererMode](-plane-renderer-mode/index.md)<br>Determines how tracked planes should be visualized on the screen. Two options are available, RENDER_ALL and RENDER_TOP_MOST. To see all tracked planes which are visible to the camera set the PlaneRendererMode to RENDER_ALL. This mode eats up quite a few resources and should only be set with care. To optimize the rendering set the mode to RENDER_TOP_MOST. In that case only the top most plane visible to a camera is rendered on the screen. Especially on weaker smartphone models this improves the overall performance. |
| [shadowMaterialInstance](shadow-material-instance.md) | [androidJvm]<br>var [shadowMaterialInstance](shadow-material-instance.md): MaterialInstance? = null |
