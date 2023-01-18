//[arsceneview](../../../index.md)/[io.github.sceneview.ar.camera](../index.md)/[ArCameraStream](index.md)

# ArCameraStream

[androidJvm]\
class [ArCameraStream](index.md)(lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md), val standardMaterialLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;sceneview/materials/camera_stream_standard.filamat&quot;, val depthOcclusionMaterialLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;sceneview/materials/camera_stream_depth.filamat&quot;) : [ArSceneLifecycleObserver](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md)

###  Displays the Camera stream using Filament.

## Constructors

| | |
|---|---|
| [ArCameraStream](-ar-camera-stream.md) | [androidJvm]<br>fun [ArCameraStream](-ar-camera-stream.md)(lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md), standardMaterialLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;sceneview/materials/camera_stream_standard.filamat&quot;, depthOcclusionMaterialLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;sceneview/materials/camera_stream_depth.filamat&quot;) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [onArFrame](on-ar-frame.md) | [androidJvm]<br>open override fun [onArFrame](on-ar-frame.md)(arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) |
| [onArSessionConfigChanged](on-ar-session-config-changed.md) | [androidJvm]<br>open override fun [onArSessionConfigChanged](on-ar-session-config-changed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), config: Config) |
| [onArSessionCreated](on-ar-session-created.md) | [androidJvm]<br>open override fun [onArSessionCreated](on-ar-session-created.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](index.md#1057561704%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onDestroy](index.md#1057561704%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [cameraTexture](camera-texture.md) | [androidJvm]<br>var [cameraTexture](camera-texture.md): Texture? = null<br>We apply the multithreaded actual rendering texture |
| [cameraTextureIds](camera-texture-ids.md) | [androidJvm]<br>val [cameraTextureIds](camera-texture-ids.md): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html)<br>Passing multiple textures allows for a multithreaded rendering pipeline |
| [cameraTextures](camera-textures.md) | [androidJvm]<br>var [cameraTextures](camera-textures.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Texture&gt;? = null<br>The init is done when we have the session frame size |
| [depthOcclusionMaterial](depth-occlusion-material.md) | [androidJvm]<br>var [depthOcclusionMaterial](depth-occlusion-material.md): MaterialInstance |
| [depthOcclusionMaterialLocation](depth-occlusion-material-location.md) | [androidJvm]<br>val [depthOcclusionMaterialLocation](depth-occlusion-material-location.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [depthTexture](depth-texture.md) | [androidJvm]<br>var [depthTexture](depth-texture.md): Texture? = null |
| [isDepthOcclusionEnabled](is-depth-occlusion-enabled.md) | [androidJvm]<br>var [isDepthOcclusionEnabled](is-depth-occlusion-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>This will process the incoming DepthImage to occlude virtual objects behind real world objects. |
| [material](material.md) | [androidJvm]<br>var [material](material.md): MaterialInstance<br>Depending on [isDepthOcclusionEnabled](is-depth-occlusion-enabled.md) and device Depth compatibility |
| [priority](priority.md) | [androidJvm]<br>var [priority](priority.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [renderable](renderable.md) | [androidJvm]<br>val [renderable](renderable.md): [Renderable](../../../../sceneview/io.github.sceneview.renderable/-renderable/index.md) |
| [standardMaterial](standard-material.md) | [androidJvm]<br>var [standardMaterial](standard-material.md): MaterialInstance |
| [standardMaterialLocation](standard-material-location.md) | [androidJvm]<br>val [standardMaterialLocation](standard-material-location.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
