//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[NodesManipulator](index.md)

# NodesManipulator

[androidJvm]\
open class [NodesManipulator](index.md)(val engine: Engine, val selectionNode: ([Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623)) -&gt; [Node](../../io.github.sceneview.nodes/-node/index.md)?)

## Constructors

| | |
|---|---|
| [NodesManipulator](-nodes-manipulator.md) | [androidJvm]<br>fun [NodesManipulator](-nodes-manipulator.md)(engine: Engine, selectionNode: ([Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623)) -&gt; [Node](../../io.github.sceneview.nodes/-node/index.md)?) |

## Types

| Name | Summary |
|---|---|
| [SelectionMode](-selection-mode/index.md) | [androidJvm]<br>enum [SelectionMode](-selection-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[NodesManipulator.SelectionMode](-selection-mode/index.md)&gt; |

## Functions

| Name | Summary |
|---|---|
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [getSelectedNode](get-selected-node.md) | [androidJvm]<br>fun [getSelectedNode](get-selected-node.md)(): [Node](../../io.github.sceneview.nodes/-node/index.md)? |
| [getSelectedNodes](get-selected-nodes.md) | [androidJvm]<br>fun [getSelectedNodes](get-selected-nodes.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../../io.github.sceneview.nodes/-node/index.md)&gt; |
| [onMove](on-move.md) | [androidJvm]<br>fun [onMove](on-move.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md), pickingResult: [SceneView.PickingResult](../../io.github.sceneview/-scene-view/-picking-result/index.md)) |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>fun [onMoveBegin](on-move-begin.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)) |
| [onRotate](on-rotate.md) | [androidJvm]<br>open fun [onRotate](on-rotate.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md), delta: Quaternion) |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>open fun [onRotateBegin](on-rotate-begin.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)) |
| [onScale](on-scale.md) | [androidJvm]<br>fun [onScale](on-scale.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md), scaleFactor: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [onScaleBegin](on-scale-begin.md) | [androidJvm]<br>fun [onScaleBegin](on-scale-begin.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)) |
| [onTap](on-tap.md) | [androidJvm]<br>open fun [onTap](on-tap.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)?) |
| [setNodeSelected](set-node-selected.md) | [androidJvm]<br>fun [setNodeSelected](set-node-selected.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md), selected: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setSelectedNode](set-selected-node.md) | [androidJvm]<br>fun [setSelectedNode](set-selected-node.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)) |
| [setSelectedNodes](set-selected-nodes.md) | [androidJvm]<br>fun [setSelectedNodes](set-selected-nodes.md)(nodes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../../io.github.sceneview.nodes/-node/index.md)&gt;) |
| [setTransformEditable](set-transform-editable.md) | [androidJvm]<br>fun [setTransformEditable](set-transform-editable.md)(editable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [allowDeselection](allow-deselection.md) | [androidJvm]<br>var [allowDeselection](allow-deselection.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>Whether it is possible to deselect nodes |
| [engine](engine.md) | [androidJvm]<br>val [engine](engine.md): Engine |
| [isPositionEditable](is-position-editable.md) | [androidJvm]<br>var [isPositionEditable](is-position-editable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [isRotationEditable](is-rotation-editable.md) | [androidJvm]<br>var [isRotationEditable](is-rotation-editable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [isScaleEditable](is-scale-editable.md) | [androidJvm]<br>var [isScaleEditable](is-scale-editable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [scaleRange](scale-range.md) | [androidJvm]<br>var [scaleRange](scale-range.md): [ClosedFloatingPointRange](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-floating-point-range/index.html)&lt;[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)&gt; |
| [selectionMode](selection-mode.md) | [androidJvm]<br>var [selectionMode](selection-mode.md): [NodesManipulator.SelectionMode](-selection-mode/index.md) |
| [selectionNode](selection-node.md) | [androidJvm]<br>val [selectionNode](selection-node.md): ([Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623)) -&gt; [Node](../../io.github.sceneview.nodes/-node/index.md)? |
| [selectNodeOnEditBegin](select-node-on-edit-begin.md) | [androidJvm]<br>var [selectNodeOnEditBegin](select-node-on-edit-begin.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
