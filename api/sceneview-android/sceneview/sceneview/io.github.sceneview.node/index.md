//[sceneview](../../index.md)/[io.github.sceneview.node](index.md)

# Package io.github.sceneview.node

## Types

| Name | Summary |
|---|---|
| [LightNode](-light-node/index.md) | [androidJvm]<br>open class [LightNode](-light-node/index.md) : [Node](-node/index.md)<br>This node contains a light for the rendering engine to render. |
| [ModelNode](-model-node/index.md) | [androidJvm]<br>open class [ModelNode](-model-node/index.md) : [RenderableNode](-renderable-node/index.md)<br>This node contains a renderable model for the rendering engine to render. |
| [Node](-node/index.md) | [androidJvm]<br>open class [Node](-node/index.md)(position: [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = DEFAULT_POSITION, quaternion: [Quaternion](../dev.romainguy.kotlin.math/-quaternion/index.md) = DEFAULT_QUATERNION, scale: [Scale](../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623) = DEFAULT_SCALE) : [NodeParent](-node-parent/index.md), [TransformProvider](../com.google.ar.sceneform.common/-transform-provider/index.md), [SceneLifecycleObserver](../io.github.sceneview/-scene-lifecycle-observer/index.md), [GestureDetector.OnGestureListener](../io.github.sceneview.gesture/-gesture-detector/-on-gesture-listener/index.md)<br>It can contain a renderable for the rendering engine to render. |
| [NodeParent](-node-parent/index.md) | [androidJvm]<br>interface [NodeParent](-node-parent/index.md)<br>The classes [Node](-node/index.md) and Scene are both NodeParents. To make a [Node](-node/index.md) the child of another [Node](-node/index.md) or a Scene, use Node.setParent. |
| [RenderableNode](-renderable-node/index.md) | [androidJvm]<br>open class [RenderableNode](-renderable-node/index.md) : [Node](-node/index.md)<br>This node contains a renderable model for the rendering engine to render. |
| [ViewNode](-view-node/index.md) | [androidJvm]<br>open class [ViewNode](-view-node/index.md) : [Node](-node/index.md)<br>This node contains a View for the rendering engine to render. |
