//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Renderer](index.md)

# Renderer

[androidJvm]\
open class [Renderer](index.md) : UiHelper.RendererCallback

A rendering context. 

Contains everything that will be drawn on a surface.

## Constructors

| | |
|---|---|
| [Renderer](-renderer.md) | [androidJvm]<br>@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))<br>open fun [Renderer](-renderer.md)(view: [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html), cameraProvider: [CameraProvider](../-camera-provider/index.md)) |

## Types

| Name | Summary |
|---|---|
| [PreRenderCallback](-pre-render-callback/index.md) | [androidJvm]<br>interface [PreRenderCallback](-pre-render-callback/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addEntity](add-entity.md) | [androidJvm]<br>open fun [addEntity](add-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addLight](add-light.md) | [androidJvm]<br>open fun [addLight](add-light.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [destroyAllResources](destroy-all-resources.md) | [androidJvm]<br>open fun [destroyAllResources](destroy-all-resources.md)()<br>Immediately releases all rendering resources, even if in use. |
| [dispose](dispose.md) | [androidJvm]<br>open fun [dispose](dispose.md)() |
| [enablePerformanceMode](enable-performance-mode.md) | [androidJvm]<br>open fun [enablePerformanceMode](enable-performance-mode.md)()<br>Sets a high performance configuration for the filament view. |
| [getContext](get-context.md) | [androidJvm]<br>open fun [getContext](get-context.md)(): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) |
| [getDesiredHeight](get-desired-height.md) | [androidJvm]<br>open fun [getDesiredHeight](get-desired-height.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDesiredWidth](get-desired-width.md) | [androidJvm]<br>open fun [getDesiredWidth](get-desired-width.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getFilamentRenderer](get-filament-renderer.md) | [androidJvm]<br>open fun [getFilamentRenderer](get-filament-renderer.md)(): Renderer<br>Access to the underlying Filament renderer. |
| [getFilamentScene](get-filament-scene.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [getFilamentScene](get-filament-scene.md)(): Scene |
| [getFilamentView](get-filament-view.md) | [androidJvm]<br>open fun [getFilamentView](get-filament-view.md)(): View<br>Access to the underlying Filament view. |
| [isFrontFaceWindingInverted](is-front-face-winding-inverted.md) | [androidJvm]<br>open fun [isFrontFaceWindingInverted](is-front-face-winding-inverted.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks whether winding is inverted for front face rendering. |
| [onDetachedFromSurface](on-detached-from-surface.md) | [androidJvm]<br>open fun [onDetachedFromSurface](on-detached-from-surface.md)() |
| [onNativeWindowChanged](on-native-window-changed.md) | [androidJvm]<br>open fun [onNativeWindowChanged](on-native-window-changed.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html)) |
| [onPause](on-pause.md) | [androidJvm]<br>open fun [onPause](on-pause.md)() |
| [onResized](on-resized.md) | [androidJvm]<br>open fun [onResized](on-resized.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [onResume](on-resume.md) | [androidJvm]<br>open fun [onResume](on-resume.md)() |
| [reclaimReleasedResources](reclaim-released-resources.md) | [androidJvm]<br>open fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Releases rendering resources ready for garbage collection |
| [removeEntity](remove-entity.md) | [androidJvm]<br>open fun [removeEntity](remove-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [removeLight](remove-light.md) | [androidJvm]<br>open fun [removeLight](remove-light.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [render](render.md) | [androidJvm]<br>open fun [render](render.md)(frameTimeNanos: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAntiAliasing](set-anti-aliasing.md) | [androidJvm]<br>open fun [setAntiAliasing](set-anti-aliasing.md)(antiAliasing: View.AntiAliasing) |
| [setClearColor](set-clear-color.md) | [androidJvm]<br>open fun [setClearColor](set-clear-color.md)(color: [Float4](../../dev.romainguy.kotlin.math/-float4/index.md)) |
| [setDefaultClearColor](set-default-clear-color.md) | [androidJvm]<br>open fun [setDefaultClearColor](set-default-clear-color.md)() |
| [setDesiredSize](set-desired-size.md) | [androidJvm]<br>open fun [setDesiredSize](set-desired-size.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setDithering](set-dithering.md) | [androidJvm]<br>open fun [setDithering](set-dithering.md)(dithering: View.Dithering) |
| [setDynamicResolutionEnabled](set-dynamic-resolution-enabled.md) | [androidJvm]<br>open fun [setDynamicResolutionEnabled](set-dynamic-resolution-enabled.md)(isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setFrameRenderDebugCallback](set-frame-render-debug-callback.md) | [androidJvm]<br>open fun [setFrameRenderDebugCallback](set-frame-render-debug-callback.md)(onFrameRenderDebugCallback: [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html))<br>Sets a callback to happen after each frame is rendered. |
| [setFrontFaceWindingInverted](set-front-face-winding-inverted.md) | [androidJvm]<br>open fun [setFrontFaceWindingInverted](set-front-face-winding-inverted.md)(inverted: [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html))<br>Inverts winding for front face rendering. |
| [setIndirectLight](set-indirect-light.md) | [androidJvm]<br>open fun [setIndirectLight](set-indirect-light.md)(indirectLight: IndirectLight)<br>Sets the environment light used for reflections and indirect light. |
| [setPostProcessingEnabled](set-post-processing-enabled.md) | [androidJvm]<br>open fun [setPostProcessingEnabled](set-post-processing-enabled.md)(enablePostProcessing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setRenderQuality](set-render-quality.md) | [androidJvm]<br>open fun [setRenderQuality](set-render-quality.md)(renderQuality: View.RenderQuality) |
| [setSkybox](set-skybox.md) | [androidJvm]<br>open fun [setSkybox](set-skybox.md)(skybox: Skybox)<br>Sets the Skybox. |
| [startMirroring](start-mirroring.md) | [androidJvm]<br>open fun [startMirroring](start-mirroring.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Starts mirroring to the specified [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). |
| [stopMirroring](stop-mirroring.md) | [androidJvm]<br>open fun [stopMirroring](stop-mirroring.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html))<br>Stops mirroring to the specified [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). |

## Properties

| Name | Summary |
|---|---|
| [camera](camera.md) | [androidJvm]<br>private open val [camera](camera.md): Camera |
| [environment](environment.md) | [androidJvm]<br>open var [environment](environment.md): [Environment](../../io.github.sceneview.environment/-environment/index.md) |
| [mainLight](main-light.md) | [androidJvm]<br>open var [mainLight](main-light.md): [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html) |
| [preRenderCallback](pre-render-callback.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [preRenderCallback](pre-render-callback.md): [Renderer.PreRenderCallback](-pre-render-callback/index.md) |
| [surfaceView](surface-view.md) | [androidJvm]<br>private val [surfaceView](surface-view.md): [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html) |
