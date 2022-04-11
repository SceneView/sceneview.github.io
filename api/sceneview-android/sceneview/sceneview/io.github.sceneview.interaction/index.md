//[sceneview](../../index.md)/[io.github.sceneview.interaction](index.md)

# Package io.github.sceneview.interaction

## Types

| Name | Summary |
|---|---|
| [FilamentGestureDetector](index.md#-1705903723%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [FilamentGestureDetector](index.md#-1705903723%2FClasslikes%2F-1571379623) = GestureDetector |
| [MoveGestureDetector](-move-gesture-detector/index.md) | [androidJvm]<br>class [MoveGestureDetector](-move-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveGestureListener](-move-gesture-detector/-on-move-gesture-listener/index.md)) |
| [RotateGestureDetector](-rotate-gesture-detector/index.md) | [androidJvm]<br>class [RotateGestureDetector](-rotate-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateGestureListener](-rotate-gesture-detector/-on-rotate-gesture-listener/index.md), handler: [Handler](https://developer.android.com/reference/kotlin/android/os/Handler.html)?)<br>The [OnRotateGestureListener](-rotate-gesture-detector/-on-rotate-gesture-listener/index.md) callback will notify users when a particular gesture event has occurred. |
| [SceneGestureDetector](-scene-gesture-detector/index.md) | [androidJvm]<br>open class [SceneGestureDetector](-scene-gesture-detector/index.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), listener: [SceneGestureDetector.OnSceneGestureListener](-scene-gesture-detector/-on-scene-gesture-listener/index.md)?, cameraManipulator: Manipulator?)<br>Camera supports one-touch orbit, two-touch pan, and pinch-to-zoom. |
| [SelectedNodeVisualizer](-selected-node-visualizer/index.md) | [androidJvm]<br>class [SelectedNodeVisualizer](-selected-node-visualizer/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [SceneLifecycle](../io.github.sceneview/-scene-lifecycle/index.md), nodeSelectorModel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [SceneLifecycleObserver](../io.github.sceneview/-scene-lifecycle-observer/index.md) |

## Properties

| Name | Summary |
|---|---|
| [defaultNodeSelector](default-node-selector.md) | [androidJvm]<br>const val [defaultNodeSelector](default-node-selector.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transform](transform.md) | [androidJvm]<br>val Manipulator.[transform](transform.md): [Transform](../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623) |
