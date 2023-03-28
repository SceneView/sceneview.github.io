//[sceneview](../../index.md)/[io.github.sceneview](index.md)

# Package io.github.sceneview

## Types

| Name | Summary |
|---|---|
| [Filament](-filament/index.md) | [androidJvm]<br>object [Filament](-filament/index.md) |
| [SceneLifecycle](-scene-lifecycle/index.md) | [androidJvm]<br>open class [SceneLifecycle](-scene-lifecycle/index.md)(val sceneView: [SceneView](-scene-view/index.md)) : [DefaultLifecycle](../io.github.sceneview.utils/-default-lifecycle/index.md) |
| [SceneLifecycleObserver](-scene-lifecycle-observer/index.md) | [androidJvm]<br>interface [SceneLifecycleObserver](-scene-lifecycle-observer/index.md) : [DefaultLifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/DefaultLifecycleObserver.html) |
| [SceneLifecycleOwner](-scene-lifecycle-owner/index.md) | [androidJvm]<br>interface [SceneLifecycleOwner](-scene-lifecycle-owner/index.md) : [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)<br>A SurfaceView that integrates with ARCore and renders a scene. |
| [SceneView](-scene-view/index.md) | [androidJvm]<br>open class [SceneView](-scene-view/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)? = null, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, cameraNode: [CameraNode](../com.google.ar.sceneform/-camera-node/index.md) = CameraNode()) : [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html), [SceneLifecycleOwner](-scene-lifecycle-owner/index.md), [DefaultLifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/DefaultLifecycleObserver.html), [Choreographer.FrameCallback](https://developer.android.com/reference/kotlin/android/view/Choreographer.FrameCallback.html), [NodeParent](../io.github.sceneview.node/-node-parent/index.md), [GestureDetector.OnGestureListener](../io.github.sceneview.gesture/-gesture-detector/-on-gesture-listener/index.md)<br>Maintains the scene graph, a hierarchical organization of a scene's content. A scene can have zero or more child nodes and each node can have zero or more child nodes. The Scene also provides hit testing, a way to detect which node is touched by a MotionEvent or Ray. |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun RenderableManager.Builder.[build](build.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [createCamera](create-camera.md) | [androidJvm]<br>fun Engine.[createCamera](create-camera.md)(): Camera |
| [Scene](-scene.md) | [androidJvm]<br>@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)<br>fun [Scene](-scene.md)(modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, nodes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../io.github.sceneview.node/-node/index.md)&gt; = listOf(), onCreate: ([SceneView](-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null) |
| [setTransform](set-transform.md) | [androidJvm]<br>fun TransformManager.[setTransform](set-transform.md)(i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worldTransform: [Transform](../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)) |

## Properties

| Name | Summary |
|---|---|
| [defaultIblLocation](default-ibl-location.md) | [androidJvm]<br>const val [defaultIblLocation](default-ibl-location.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
