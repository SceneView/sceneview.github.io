//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[SelectedNodeVisualizer](index.md)

# SelectedNodeVisualizer

[androidJvm]\
class [SelectedNodeVisualizer](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), nodeSelectorModel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [SceneLifecycleObserver](../../io.github.sceneview/-scene-lifecycle-observer/index.md)

###  Visualizes that a [Node](../../io.github.sceneview.node/-node/index.md) is selected by rendering a footprint for the selected node

## Constructors

| | |
|---|---|
| [SelectedNodeVisualizer](-selected-node-visualizer.md) | [androidJvm]<br>fun [SelectedNodeVisualizer](-selected-node-visualizer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), nodeSelectorModel: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = defaultNodeSelector) |

## Functions

| Name | Summary |
|---|---|
| [onCreate](../../io.github.sceneview.node/-view-node/index.md#139941652%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onCreate](../../io.github.sceneview.node/-view-node/index.md#139941652%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](on-destroy.md) | [androidJvm]<br>open override fun [onDestroy](on-destroy.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onFrame](../../io.github.sceneview/-scene-lifecycle-observer/on-frame.md) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview/-scene-lifecycle-observer/on-frame.md)(frameTime: [FrameTime](../../io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.node/-view-node/index.md#187777572%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.node/-view-node/index.md#187777572%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](../../io.github.sceneview.node/-view-node/index.md#-1807945979%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onResume](../../io.github.sceneview.node/-view-node/index.md#-1807945979%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.node/-view-node/index.md#1240777104%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.node/-view-node/index.md#1240777104%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.node/-view-node/index.md#487071706%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.node/-view-node/index.md#487071706%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Records a change in surface dimensions. |
| [selectNode](select-node.md) | [androidJvm]<br>fun [selectNode](select-node.md)(node: [Node](../../io.github.sceneview.node/-node/index.md), selected: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [lifecycle](lifecycle.md) | [androidJvm]<br>val [lifecycle](lifecycle.md): [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html) |
