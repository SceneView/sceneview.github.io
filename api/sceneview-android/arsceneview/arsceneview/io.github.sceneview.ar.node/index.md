//[arsceneview](../../index.md)/[io.github.sceneview.ar.node](index.md)

# Package io.github.sceneview.ar.node

## Types

| Name | Summary |
|---|---|
| [ArModelNode](-ar-model-node/index.md) | [androidJvm]<br>open class [ArModelNode](-ar-model-node/index.md) : [ArNode](-ar-node/index.md)<br>This [io.github.sceneview.node.Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md) follows the actual ARCore detected orientation and position at the provided relative X, Y location in the [ArSceneView](../io.github.sceneview.ar/-ar-scene-view/index.md) |
| [ArNode](-ar-node/index.md) | [androidJvm]<br>open class [ArNode](-ar-node/index.md) : [ModelNode](../../../sceneview/sceneview/io.github.sceneview.node/-model-node/index.md), [ArSceneLifecycleObserver](../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md) |
| [CursorNode](-cursor-node/index.md) | [androidJvm]<br>open class [CursorNode](-cursor-node/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), modelFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;sceneview/models/cursor.glb&quot;, autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, scaleToUnits: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, centerOrigin: [Position](../../../sceneview/io.github.sceneview.math/-position/index.md)? = null, onError: ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onLoaded: ([ModelInstance](../../../sceneview/io.github.sceneview.model/-model-instance/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null) : [ArModelNode](-ar-model-node/index.md) |
| [PlacementMode](-placement-mode/index.md) | [androidJvm]<br>enum [PlacementMode](-placement-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PlacementMode](-placement-mode/index.md)&gt; |
