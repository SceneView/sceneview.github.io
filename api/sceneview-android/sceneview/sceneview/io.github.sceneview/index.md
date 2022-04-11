//[sceneview](../../index.md)/[io.github.sceneview](index.md)

# Package io.github.sceneview

## Types

| Name | Summary |
|---|---|
| [Filament](-filament/index.md) | [androidJvm]<br>object [Filament](-filament/index.md) |
| [SceneLifecycle](-scene-lifecycle/index.md) | [androidJvm]<br>open class [SceneLifecycle](-scene-lifecycle/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), owner: [SceneLifecycleOwner](-scene-lifecycle-owner/index.md)) : [DefaultLifecycle](../io.github.sceneview.utils/-default-lifecycle/index.md) |
| [SceneLifecycleObserver](-scene-lifecycle-observer/index.md) | [androidJvm]<br>interface [SceneLifecycleObserver](-scene-lifecycle-observer/index.md) : [DefaultLifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/DefaultLifecycleObserver.html) |
| [SceneLifecycleOwner](-scene-lifecycle-owner/index.md) | [androidJvm]<br>interface [SceneLifecycleOwner](-scene-lifecycle-owner/index.md) : [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)<br>A SurfaceView that integrates with ARCore and renders a scene. |
| [SceneView](-scene-view/index.md) | [androidJvm]<br>open class [SceneView](-scene-view/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)?, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html), [SceneLifecycleOwner](-scene-lifecycle-owner/index.md), [DefaultLifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/DefaultLifecycleObserver.html), [Choreographer.FrameCallback](https://developer.android.com/reference/kotlin/android/view/Choreographer.FrameCallback.html), [NodeParent](../io.github.sceneview.node/-node-parent/index.md)<br>Maintains the scene graph, a hierarchical organization of a scene's content. A scene can have zero or more child nodes and each node can have zero or more child nodes. The Scene also provides hit testing, a way to detect which node is touched by a MotionEvent or Ray. |

## Properties

| Name | Summary |
|---|---|
| [defaultIbl](default-ibl.md) | [androidJvm]<br>const val [defaultIbl](default-ibl.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [defaultSkybox](default-skybox.md) | [androidJvm]<br>const val [defaultSkybox](default-skybox.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
