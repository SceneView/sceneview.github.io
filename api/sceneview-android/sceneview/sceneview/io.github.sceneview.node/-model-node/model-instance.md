//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[modelInstance](model-instance.md)

# modelInstance

[androidJvm]\
var [modelInstance](model-instance.md): [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)? = null

###  The [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md) to display.

If [collisionShape](../../../../sceneview/io.github.sceneview.node/-model-node/collision-shape.md) is not set, then [Renderable.getCollisionShape](../../com.google.ar.sceneform.rendering/-view-renderable/index.md#111252609%2FFunctions%2F-1571379623) is used to detect collisions for this [Node](../-node/index.md).

The renderable is usually a 3D model. If null, this node's current renderable will be removed.
