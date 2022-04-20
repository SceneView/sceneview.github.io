//[sceneview](../../index.md)/[io.github.sceneview.node](index.md)

# Package io.github.sceneview.node

## Types

| Name | Summary |
|---|---|
| [LightNode](-light-node/index.md) | [androidJvm]<br>open class [LightNode](-light-node/index.md) : [Node](-node/index.md)<br>This node contains a light for the rendering engine to render. |
| [LoadingNode](-loading-node/index.md) | [androidJvm]<br>open class [LoadingNode](-loading-node/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), position: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623), rotation: [Rotation](../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623), scale: [Scale](../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623)) : [ViewNode](-view-node/index.md) |
| [ModelNode](-model-node/index.md) | [androidJvm]<br>open class [ModelNode](-model-node/index.md) : [Node](-node/index.md)<br>This node contains a renderable for the rendering engine to render. |
| [Node](-node/index.md) | [androidJvm]<br>open class [Node](-node/index.md) : [NodeParent](-node-parent/index.md), [TransformProvider](../com.google.ar.sceneform.common/-transform-provider/index.md), [SceneLifecycleObserver](../io.github.sceneview/-scene-lifecycle-observer/index.md)<br>It can contain a renderable for the rendering engine to render. |
| [NodeParent](-node-parent/index.md) | [androidJvm]<br>interface [NodeParent](-node-parent/index.md)<br>The classes [Node](-node/index.md) and Scene are both NodeParents. To make a [Node](-node/index.md) the child of another [Node](-node/index.md) or a Scene, use Node.setParent. |
| [OnModelLoaded](index.md#899098479%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [OnModelLoaded](index.md#899098479%2FClasslikes%2F-1571379623) = (modelInstance: [RenderableInstance](../com.google.ar.sceneform.rendering/-renderable-instance/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [ViewNode](-view-node/index.md) | [androidJvm]<br>open class [ViewNode](-view-node/index.md) : [Node](-node/index.md)<br>This node contains a View for the rendering engine to render. |
