//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[NodeParent](index.md)/[callOnHierarchy](call-on-hierarchy.md)

# callOnHierarchy

[androidJvm]\
open fun [callOnHierarchy](call-on-hierarchy.md)(action: ([Node](../-node/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Traverse the hierarchy and call a method on each node.

Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children.

## Parameters

androidJvm

| | |
|---|---|
| action | The method to call on each node. |
