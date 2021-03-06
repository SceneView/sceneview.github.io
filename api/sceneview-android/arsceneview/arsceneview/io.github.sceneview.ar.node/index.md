//[arsceneview](../../index.md)/[io.github.sceneview.ar.node](index.md)

# Package io.github.sceneview.ar.node

## Types

| Name | Summary |
|---|---|
| [ArModelNode](-ar-model-node/index.md) | [androidJvm]<br>open class [ArModelNode](-ar-model-node/index.md) : [ArNode](-ar-node/index.md)<br>This [io.github.sceneview.node.Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md) follows the actual ARCore detected orientation and position at the provided relative X, Y location in the [ArSceneView](../io.github.sceneview.ar/-ar-scene-view/index.md) |
| [ArNode](-ar-node/index.md) | [androidJvm]<br>open class [ArNode](-ar-node/index.md) : [ModelNode](../../../sceneview/sceneview/io.github.sceneview.node/-model-node/index.md), [ArSceneLifecycleObserver](../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md) |
| [CursorNode](-cursor-node/index.md) | [androidJvm]<br>open class [CursorNode](-cursor-node/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)?, modelFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), autoScale: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), centerOrigin: [Position](../../../sceneview/io.github.sceneview.math/-position/index.md)?, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?, onLoaded: (instance: [RenderableInstance](../../../arsceneview/com.google.ar.sceneform.rendering/-renderable-instance/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?) : [ArModelNode](-ar-model-node/index.md) |
| [EditableTransform](-editable-transform/index.md) | [androidJvm]<br>enum [EditableTransform](-editable-transform/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[EditableTransform](-editable-transform/index.md)&gt; |
| [PlacementMode](-placement-mode/index.md) | [androidJvm]<br>enum [PlacementMode](-placement-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PlacementMode](-placement-mode/index.md)&gt; |
