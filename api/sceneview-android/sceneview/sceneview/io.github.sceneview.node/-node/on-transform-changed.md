//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[onTransformChanged](on-transform-changed.md)

# onTransformChanged

[androidJvm]\
open fun [onTransformChanged](on-transform-changed.md)()

val [onTransformChanged](on-transform-changed.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(node: [Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;

###  The transformation (position, rotation or scale) of the [Node](index.md) has changed

If node A's position is changed, then that will trigger [onTransformChanged](on-transform-changed.md) to be called for all of it's descendants.
