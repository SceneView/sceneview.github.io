//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[LightEstimation](index.md)

# LightEstimation

[androidJvm]\
class [LightEstimation](index.md)(sceneView: [ArSceneView](../../io.github.sceneview.ar/-ar-scene-view/index.md), lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md)) : [ArSceneLifecycleObserver](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md)

###  Per frame AR light estimation

ARCore will estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation

A key part for creating realistic AR experiences is getting the lighting right. When a virtual object is missing a shadow or has a shiny material that doesn't reflect the surrounding space, users can sense that the object doesn't quite fit, even if they can't explain why. This is because humans subconsciously perceive cues regarding how objects are lit in their environment. The Lighting Estimation API analyzes given images for such cues, providing detailed information about the lighting in a scene. You can then use this information when rendering virtual objects to light them under the same conditions as the scene they're placed in, keeping users grounded and engaged.

## Constructors

| | |
|---|---|
| [LightEstimation](-light-estimation.md) | [androidJvm]<br>fun [LightEstimation](-light-estimation.md)(sceneView: [ArSceneView](../../io.github.sceneview.ar/-ar-scene-view/index.md), lifecycle: [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [onArFrame](on-ar-frame.md) | [androidJvm]<br>open override fun [onArFrame](on-ar-frame.md)(arFrame: [ArFrame](../-ar-frame/index.md)) |
| [onArSessionConfigChanged](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-config-changed.md) | [androidJvm]<br>open fun [onArSessionConfigChanged](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-config-changed.md)(session: [ArSession](../-ar-session/index.md), config: Config) |
| [onArSessionCreated](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-created.md) | [androidJvm]<br>open fun [onArSessionCreated](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-created.md)(session: [ArSession](../-ar-session/index.md)) |
| [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](../../io.github.sceneview.ar/-ar-scene-lifecycle-observer/on-ar-session-resumed.md)(session: [ArSession](../-ar-session/index.md)) |
| [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onCreate](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#139941652%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](on-destroy.md) | [androidJvm]<br>open override fun [onDestroy](on-destroy.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onResume](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#-1807945979%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [cameraExposureFactor](camera-exposure-factor.md) | [androidJvm]<br>var [cameraExposureFactor](camera-exposure-factor.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>ARCore's light estimation uses unit-less (relative) values while Filament uses a physically based camera model with lux or lumen values. In order to keep the "standard" Filament behavior we scale AR Core values. Infos: https://github.com/ThomasGorisse/SceneformMaintained/pull/156#issuecomment-911873565 |
| [cubeMapBuffer](cube-map-buffer.md) | [androidJvm]<br>var [cubeMapBuffer](cube-map-buffer.md): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)? = null |
| [cubeMapTexture](cube-map-texture.md) | [androidJvm]<br>var [cubeMapTexture](cube-map-texture.md): Texture? = null |
| [defaultEnvironmentReflections](default-environment-reflections.md) | [androidJvm]<br>var [defaultEnvironmentReflections](default-environment-reflections.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>If [environmentalHdrReflections](environmental-hdr-reflections.md) is false, use or not the [SceneView.environment](../../io.github.sceneview.ar/-ar-scene-view/index.md#-769674583%2FProperties%2F-58641720) default reflections. In case of false, and [environmentalHdrReflections](environmental-hdr-reflections.md) no reflections will come on your reflective objects. |
| [environment](environment.md) | [androidJvm]<br>var [environment](environment.md): [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md)? = null<br>Environmental HDR mode uses machine learning to analyze the camera images in real time and synthesize environmental lighting to support realistic rendering of virtual objects. |
| [environmentalHdrMainLightDirection](environmental-hdr-main-light-direction.md) | [androidJvm]<br>var [environmentalHdrMainLightDirection](environmental-hdr-main-light-direction.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>When the main light source or a lit object is in motion, the specular highlight on the object adjusts its position in real time relative to the light source. |
| [environmentalHdrMainLightIntensity](environmental-hdr-main-light-intensity.md) | [androidJvm]<br>var [environmentalHdrMainLightIntensity](environmental-hdr-main-light-intensity.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [environmentalHdrReflections](environmental-hdr-reflections.md) | [androidJvm]<br>var [environmentalHdrReflections](environmental-hdr-reflections.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>Use the HDR cubemap to render realistic reflections on virtual objects with medium to high glossiness, such as shiny metallic surfaces. The cubemap also affects the shading and appearance of objects. For example, the material of a specular object surrounded by a blue environment will reflect blue hues. Calculating the HDR cubemap requires a small amount of additional CPU computation. |
| [environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md) | [androidJvm]<br>var [environmentalHdrSpecularFilter](environmental-hdr-specular-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>Specular highlights are the shiny bits of surfaces that reflect a light source directly. Highlights on an object change relative to the position of a viewer in a scene. |
| [environmentalHdrSphericalHarmonics](environmental-hdr-spherical-harmonics.md) | [androidJvm]<br>var [environmentalHdrSphericalHarmonics](environmental-hdr-spherical-harmonics.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>In addition to the light energy in the main directional light, ARCore provides spherical harmonics, representing the overall ambient light coming in from all directions in the scene. Add subtle cues that bring out the definition of virtual objects. |
| [lastArFrame](last-ar-frame.md) | [androidJvm]<br>var [lastArFrame](last-ar-frame.md): [ArFrame](../-ar-frame/index.md)? = null |
| [lifecycle](lifecycle.md) | [androidJvm]<br>val [lifecycle](lifecycle.md): [ArSceneLifecycle](../../io.github.sceneview.ar/-ar-scene-lifecycle/index.md) |
| [mainLight](main-light.md) | [androidJvm]<br>var [mainLight](main-light.md): [Light](../../../../sceneview/io.github.sceneview.light/-light/index.md)? = null<br>The main directional light API calculates the direction and intensity of the scene's main light source. This information allows virtual objects in your scene to show reasonably positioned specular highlights, and to cast shadows in a direction consistent with other visible real objects. |
| [mode](mode.md) | [androidJvm]<br>var [mode](mode.md): [LightEstimationMode](../-light-estimation-mode/index.md)<br>ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation |
| [precision](precision.md) | [androidJvm]<br>var [precision](precision.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [renderer](renderer.md) | [androidJvm]<br>val [renderer](renderer.md): [Renderer](../../../../arsceneview/com.google.ar.sceneform.rendering/-renderer/index.md) |
| [sceneView](scene-view.md) | [androidJvm]<br>val [sceneView](scene-view.md): [ArSceneView](../../io.github.sceneview.ar/-ar-scene-view/index.md) |
| [timestamp](timestamp.md) | [androidJvm]<br>var [timestamp](timestamp.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
