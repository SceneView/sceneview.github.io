//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[NodeParent](index.md)

# NodeParent

[androidJvm]\
interface [NodeParent](index.md)

###  Base class for all classes that can contain a set of nodes as children.

The classes [Node](../-node/index.md) and Scene are both NodeParents. To make a [Node](../-node/index.md) the child of another [Node](../-node/index.md) or a Scene, use Node.setParent.

## Functions

| Name | Summary |
|---|---|
| [addChild](add-child.md) | [androidJvm]<br>open fun [addChild](add-child.md)(child: [Node](../-node/index.md)): [Node](../-node/index.md)<br>Adds a node as a child of this NodeParent. If the node already has a parent, it is removed from its old parent. If the node is already a direct child of this NodeParent, no change is made. |
| [callOnHierarchy](call-on-hierarchy.md) | [androidJvm]<br>open fun [callOnHierarchy](call-on-hierarchy.md)(action: ([Node](../-node/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [onChildAdded](on-child-added.md) | [androidJvm]<br>open fun [onChildAdded](on-child-added.md)(child: [Node](../-node/index.md)) |
| [onChildRemoved](on-child-removed.md) | [androidJvm]<br>open fun [onChildRemoved](on-child-removed.md)(child: [Node](../-node/index.md)) |
| [removeChild](remove-child.md) | [androidJvm]<br>open fun [removeChild](remove-child.md)(child: [Node](../-node/index.md)): [Node](../-node/index.md)<br>Removes a node from the children of this NodeParent. If the node is not a direct child of this NodeParent, no change is made. |

## Properties

| Name | Summary |
|---|---|
| [allChildren](all-children.md) | [androidJvm]<br>open val [allChildren](all-children.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../-node/index.md)&gt;<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [children](children.md) | [androidJvm]<br>abstract var [children](children.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../-node/index.md)&gt; |
| [hierarchy](hierarchy.md) | [androidJvm]<br>open val [hierarchy](hierarchy.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../-node/index.md)&gt;<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [onChildAdded](on-child-added.md) | [androidJvm]<br>open val [onChildAdded](on-child-added.md): ([Node](../-node/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [onChildRemoved](on-child-removed.md) | [androidJvm]<br>open val [onChildRemoved](on-child-removed.md): ([Node](../-node/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |

## Inheritors

| Name |
|---|
| [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| [Node](../-node/index.md) |
