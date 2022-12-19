//[sceneview](../../../index.md)/[io.github.sceneview.managers](../index.md)/[NodeManager](index.md)

# NodeManager

[androidJvm]\
class [NodeManager](index.md)(val engine: Engine)

## Constructors

| | |
|---|---|
| [NodeManager](-node-manager.md) | [androidJvm]<br>fun [NodeManager](-node-manager.md)(engine: Engine) |

## Functions

| Name | Summary |
|---|---|
| [addComponent](add-component.md) | [androidJvm]<br>fun [addComponent](add-component.md)(e: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623), node: [Node](../../io.github.sceneview.nodes/-node/index.md)) |
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [destroyNode](destroy-node.md) | [androidJvm]<br>fun [destroyNode](destroy-node.md)(e: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)) |
| [empty](empty.md) | [androidJvm]<br>fun [empty](empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](get.md) | [androidJvm]<br>operator fun [get](get.md)(entity: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)): [Node](../../io.github.sceneview.nodes/-node/index.md)? |
| [getComponentCount](get-component-count.md) | [androidJvm]<br>fun [getComponentCount](get-component-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEntity](get-entity.md) | [androidJvm]<br>fun [getEntity](get-entity.md)(node: [Node](../../io.github.sceneview.nodes/-node/index.md)): [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)? |
| [getNode](get-node.md) | [androidJvm]<br>fun [getNode](get-node.md)(e: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)): [Node](../../io.github.sceneview.nodes/-node/index.md)? |
| [hasComponent](has-component.md) | [androidJvm]<br>fun [hasComponent](has-component.md)(e: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeComponent](remove-component.md) | [androidJvm]<br>fun [removeComponent](remove-component.md)(e: [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)) |

## Properties

| Name | Summary |
|---|---|
| [engine](engine.md) | [androidJvm]<br>val [engine](engine.md): Engine |
| [entities](entities.md) | [androidJvm]<br>val [entities](entities.md): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)&lt;[Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623)&gt; |
