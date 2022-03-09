//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[onRenderingChanged](on-rendering-changed.md)

# onRenderingChanged

[androidJvm]\
open fun [onRenderingChanged](on-rendering-changed.md)(isRendering: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

###  Handles when this node becomes rendered (displayed) or not

A Node is rendered if it's visible, part of a scene, and its parent is rendered. Override to perform any setup that needs to occur when the node is active or not.

[androidJvm]\
val [onRenderingChanged](on-rendering-changed.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(node: [Node](index.md), isRendering: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;

###  Listener for [onRenderingChanged](on-rendering-changed.md) call
