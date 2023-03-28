//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.nodes](index.md)

# Package io.github.sceneview.nodes

## Types

| Name | Summary |
|---|---|
| [CameraNode](-camera-node/index.md) | [androidJvm]<br>open class [CameraNode](-camera-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), val entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187)) : [Node](-node/index.md), [CameraComponent](../io.github.sceneview.components/-camera-component/index.md)<br>Camera represents the eye through which the scene is viewed. |
| [GeometryNode](-geometry-node/index.md) | [androidJvm]<br>open class [GeometryNode](-geometry-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), geometry: [Geometry](../io.github.sceneview.geometries/-geometry/index.md), materials: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;MaterialInstance?&gt; = listOf(), val entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187) = EntityManager.get().create(), apply: RenderableManager.Builder.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = {}) : [RenderableNode](-renderable-node/index.md), [RenderableComponent](../io.github.sceneview.components/-renderable-component/index.md)<br>Mesh are bundles of primitives, each of which has its own geometry and material. |
| [LightNode](-light-node/index.md) | [androidJvm]<br>open class [LightNode](-light-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), val entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187)) : [Node](-node/index.md), [LightComponent](../io.github.sceneview.components/-light-component/index.md)<br>Light source [Node](-node/index.md) in the scene such as a sun or street lights |
| [ModelNode](-model-node/index.md) | [androidJvm]<br>open class [ModelNode](-model-node/index.md) : [Node](-node/index.md)<br>Create the ModelNode from a loaded model instance |
| [Node](-node/index.md) | [androidJvm]<br>open class [Node](-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), val entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187) = EntityManager.get().create(), var isSelectable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, isEditable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, val sceneEntities: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187)&gt; = listOf(entity)) : [TransformComponent](../io.github.sceneview.components/-transform-component/index.md)<br>A Node represents a transformation within the scene graph's hierarchy. |
| [RenderableNode](-renderable-node/index.md) | [androidJvm]<br>open class [RenderableNode](-renderable-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), val entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187), var isSelectable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, isEditable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true) : [Node](-node/index.md), [RenderableComponent](../io.github.sceneview.components/-renderable-component/index.md) |
| [ViewNode](-view-node/index.md) | [androidJvm]<br>class [ViewNode](-view-node/index.md)(engine: Engine, nodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md), viewWindowViewManager: [WindowViewManager](../io.github.sceneview.managers/-window-view-manager/index.md), materialLoader: [MaterialLoader](../io.github.sceneview.loaders/-material-loader/index.md), view: [View](https://developer.android.com/reference/kotlin/android/view/View.html), unlit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, invertFrontFaceWinding: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) : [RenderableNode](-renderable-node/index.md), [RenderableComponent](../io.github.sceneview.components/-renderable-component/index.md)<br>A Node that can display an Android [View](https://developer.android.com/reference/kotlin/android/view/View.html) |

## Functions

| Name | Summary |
|---|---|
| [get](get.md) | [androidJvm]<br>inline operator fun &lt;[T](get.md) : [ModelNode.ChildNode](-model-node/-child-node/index.md)&gt; [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[T](get.md)&gt;.[get](get.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](get.md)? |