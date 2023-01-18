//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.utils](../index.md)/[SurfaceMirorer](index.md)

# SurfaceMirorer

[androidJvm]\
class [SurfaceMirorer](index.md)(engine: Engine, view: View, renderer: Renderer)

## Constructors

| | |
|---|---|
| [SurfaceMirorer](-surface-mirorer.md) | [androidJvm]<br>fun [SurfaceMirorer](-surface-mirorer.md)(engine: Engine, view: View, renderer: Renderer) |

## Types

| Name | Summary |
|---|---|
| [SurfaceMirror](-surface-mirror/index.md) | [androidJvm]<br>data class [SurfaceMirror](-surface-mirror/index.md)(val surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), var swapChain: SwapChain?, val viewport: Viewport) |

## Functions

| Name | Summary |
|---|---|
| [onFrame](on-frame.md) | [androidJvm]<br>fun [onFrame](on-frame.md)() |
| [startMirroring](start-mirroring.md) | [androidJvm]<br>fun [startMirroring](start-mirroring.md)(destSurface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Mirror the rendering to a surface |
| [stopMirroring](stop-mirroring.md) | [androidJvm]<br>fun [stopMirroring](stop-mirroring.md)(destSurface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html))<br>Stops mirroring to the specified [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). |
