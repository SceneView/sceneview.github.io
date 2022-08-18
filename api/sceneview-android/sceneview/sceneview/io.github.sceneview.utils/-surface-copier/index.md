//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[SurfaceCopier](index.md)

# SurfaceCopier

[androidJvm]\
class [SurfaceCopier](index.md)(lifecycle: [SceneLifecycle](../../io.github.sceneview/-scene-lifecycle/index.md)) : [SceneLifecycleObserver](../../io.github.sceneview/-scene-lifecycle-observer/index.md)

###  Displays the Camera stream using Filament.

## Constructors

| | |
|---|---|
| [SurfaceCopier](-surface-copier.md) | [androidJvm]<br>fun [SurfaceCopier](-surface-copier.md)(lifecycle: [SceneLifecycle](../../io.github.sceneview/-scene-lifecycle/index.md)) |

## Types

| Name | Summary |
|---|---|
| [SurfaceMirror](-surface-mirror/index.md) | [androidJvm]<br>data class [SurfaceMirror](-surface-mirror/index.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), swapChain: SwapChain?, viewport: Viewport) |

## Functions

| Name | Summary |
|---|---|
| [onCreate](index.md#139941652%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onCreate](index.md#139941652%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](index.md#1057561704%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onDestroy](index.md#1057561704%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](on-frame.md) | [androidJvm]<br>open override fun [onFrame](on-frame.md)(frameTime: [FrameTime](../-frame-time/index.md)) |
| [onPause](index.md#187777572%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onPause](index.md#187777572%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](index.md#-1807945979%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onResume](index.md#-1807945979%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](index.md#1240777104%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStart](index.md#1240777104%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](index.md#487071706%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStop](index.md#487071706%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Records a change in surface dimensions. |
| [startMirroring](start-mirroring.md) | [androidJvm]<br>fun [startMirroring](start-mirroring.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html), left: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, bottom: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = sceneView.width, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = sceneView.height)<br>This can be used to video record the actual SceneView rendering. |
| [stopMirroring](stop-mirroring.md) | [androidJvm]<br>fun [stopMirroring](stop-mirroring.md)(surface: [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html))<br>When capturing is complete, call this method to stop mirroring the SceneView to the specified [Surface](https://developer.android.com/reference/kotlin/android/view/Surface.html). If this is not called, the additional performance cost will remain. |
