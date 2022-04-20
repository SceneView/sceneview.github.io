//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ArRenderer](index.md)

# ArRenderer

[androidJvm]\
open class [ArRenderer](index.md) : [Renderer](../../../../arsceneview/com.google.ar.sceneform.rendering/-renderer/index.md)

A rendering context. 

Contains everything that will be drawn on a surface.

## Constructors

| | |
|---|---|
| [ArRenderer](-ar-renderer.md) | [androidJvm]<br>@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))<br>open fun [ArRenderer](-ar-renderer.md)(view: [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html), cameraProvider: [CameraProvider](../../../../arsceneview/com.google.ar.sceneform.rendering/-camera-provider/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [addEntity](index.md#-670665020%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [addEntity](index.md#-670665020%2FFunctions%2F-58641720)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addLight](index.md#2109119873%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [addLight](index.md#2109119873%2FFunctions%2F-58641720)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [destroy](index.md#-799090183%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [destroy](index.md#-799090183%2FFunctions%2F-58641720)() |
| [enablePerformanceMode](index.md#-1633815997%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [enablePerformanceMode](index.md#-1633815997%2FFunctions%2F-58641720)() |
| [getCamera](index.md#-1787714184%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getCamera](index.md#-1787714184%2FFunctions%2F-58641720)(): Camera |
| [getContext](index.md#-189225042%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getContext](index.md#-189225042%2FFunctions%2F-58641720)(): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) |
| [getDesiredHeight](index.md#-645031620%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getDesiredHeight](index.md#-645031620%2FFunctions%2F-58641720)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDesiredWidth](index.md#157348657%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getDesiredWidth](index.md#157348657%2FFunctions%2F-58641720)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEnvironment](index.md#287654858%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getEnvironment](index.md#287654858%2FFunctions%2F-58641720)(): [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md) |
| [getFilamentRenderer](index.md#-1435621020%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getFilamentRenderer](index.md#-1435621020%2FFunctions%2F-58641720)(): Renderer |
| [getFilamentScene](index.md#-1793280025%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getFilamentScene](index.md#-1793280025%2FFunctions%2F-58641720)(): Scene |
| [getFilamentView](index.md#458606274%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getFilamentView](index.md#458606274%2FFunctions%2F-58641720)(): View |
| [getMainLight](index.md#-2083335616%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getMainLight](index.md#-2083335616%2FFunctions%2F-58641720)(): [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html) |
| [getSurfaceView](index.md#-786783797%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getSurfaceView](index.md#-786783797%2FFunctions%2F-58641720)(): [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html) |
| [isFrontFaceWindingInverted](index.md#1700436020%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isFrontFaceWindingInverted](index.md#1700436020%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDetachedFromSurface](index.md#-989906943%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onDetachedFromSurface](index.md#-989906943%2FFunctions%2F-58641720)() |
| [onNativeWindowChanged](index.md#-1507042366%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onNativeWindowChanged](index.md#-1507042366%2FFunctions%2F-58641720)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html)) |
| [onPause](index.md#-791408324%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onPause](index.md#-791408324%2FFunctions%2F-58641720)() |
| [onResized](index.md#2117441093%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onResized](index.md#2117441093%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [onResume](index.md#322288667%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onResume](index.md#322288667%2FFunctions%2F-58641720)() |
| [removeEntity](index.md#1213550611%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [removeEntity](index.md#1213550611%2FFunctions%2F-58641720)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [removeLight](index.md#1754259026%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [removeLight](index.md#1754259026%2FFunctions%2F-58641720)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [render](index.md#-1281190603%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [render](index.md#-1281190603%2FFunctions%2F-58641720)(frameTimeNanos: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAntiAliasing](index.md#-1982947815%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setAntiAliasing](index.md#-1982947815%2FFunctions%2F-58641720)(antiAliasing: View.AntiAliasing) |
| [setClearColor](index.md#1974851928%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setClearColor](index.md#1974851928%2FFunctions%2F-58641720)(color: [Float4](../../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)) |
| [setDefaultClearColor](index.md#1458875954%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setDefaultClearColor](index.md#1458875954%2FFunctions%2F-58641720)() |
| [setDesiredSize](index.md#-797064807%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setDesiredSize](index.md#-797064807%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setDithering](index.md#-1436932183%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setDithering](index.md#-1436932183%2FFunctions%2F-58641720)(dithering: View.Dithering) |
| [setDynamicResolutionEnabled](index.md#366974975%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setDynamicResolutionEnabled](index.md#366974975%2FFunctions%2F-58641720)(isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setEnvironment](index.md#312329172%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setEnvironment](index.md#312329172%2FFunctions%2F-58641720)(environment: [Environment](../../../../sceneview/sceneview/io.github.sceneview.environment/-environment/index.md)) |
| [setFrameRenderDebugCallback](index.md#1471003563%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setFrameRenderDebugCallback](index.md#1471003563%2FFunctions%2F-58641720)(onFrameRenderDebugCallback: [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html)) |
| [setFrontFaceWindingInverted](index.md#-1851230330%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setFrontFaceWindingInverted](index.md#-1851230330%2FFunctions%2F-58641720)(inverted: [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)) |
| [setIndirectLight](index.md#-115495958%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setIndirectLight](index.md#-115495958%2FFunctions%2F-58641720)(indirectLight: IndirectLight) |
| [setMainLight](index.md#1574888588%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setMainLight](index.md#1574888588%2FFunctions%2F-58641720)(light: [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)) |
| [setPostProcessingEnabled](index.md#-1597081249%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setPostProcessingEnabled](index.md#-1597081249%2FFunctions%2F-58641720)(enablePostProcessing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setPreRenderCallback](index.md#-692941693%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setPreRenderCallback](index.md#-692941693%2FFunctions%2F-58641720)(preRenderCallback: [Renderer.PreRenderCallback](../../../../arsceneview/com.google.ar.sceneform.rendering/-renderer/-pre-render-callback/index.md)) |
| [setRenderQuality](index.md#-586211505%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setRenderQuality](index.md#-586211505%2FFunctions%2F-58641720)(renderQuality: View.RenderQuality) |
| [setSkybox](index.md#528419244%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setSkybox](index.md#528419244%2FFunctions%2F-58641720)(skybox: Skybox) |
| [startMirroring](index.md#1656025779%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [startMirroring](index.md#1656025779%2FFunctions%2F-58641720)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [stopMirroring](index.md#-306291665%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [stopMirroring](index.md#-306291665%2FFunctions%2F-58641720)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html)) |
