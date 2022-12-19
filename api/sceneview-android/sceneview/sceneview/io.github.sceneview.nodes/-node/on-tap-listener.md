//[sceneview](../../../index.md)/[io.github.sceneview.nodes](../index.md)/[Node](index.md)/[onTapListener](on-tap-listener.md)

# onTapListener

[androidJvm]\
var [onTapListener](on-tap-listener.md): (node: [Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

Invoked when the node is tapped

Only nodes with renderables or their parent nodes can be tapped since Filament picking is used to find a touched node. The ID of the Filament renderable can be used to determine what part of a model is tapped.
