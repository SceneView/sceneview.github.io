//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[onModelChanged](on-model-changed.md)

# onModelChanged

[androidJvm]\
open fun [onModelChanged](on-model-changed.md)(modelInstance: [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)?)

###  The transformation of the [Node](../-node/index.md) has changed

If node A's position is changed, then that will trigger [onTransformChanged](../../../../sceneview/io.github.sceneview.node/-model-node/on-transform-changed.md) to be called for all of it's descendants.

[androidJvm]\
var [onModelChanged](on-model-changed.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(modelInstance: [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;
