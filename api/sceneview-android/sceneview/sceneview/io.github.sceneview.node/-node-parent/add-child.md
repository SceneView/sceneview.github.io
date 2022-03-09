//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[NodeParent](index.md)/[addChild](add-child.md)

# addChild

[androidJvm]\

@[UiThread](https://developer.android.com/reference/kotlin/androidx/annotation/UiThread.html)

open fun [addChild](add-child.md)(child: [Node](../-node/index.md)): [Node](../-node/index.md)

Adds a node as a child of this NodeParent. If the node already has a parent, it is removed from its old parent. If the node is already a direct child of this NodeParent, no change is made.

## Parameters

androidJvm

| | |
|---|---|
| child | the node to add as a child |

## Throws

| | |
|---|---|
| [kotlin.IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html) | if the child is the same object as the parent, or if the parent is a descendant of the child |
