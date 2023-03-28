//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.geometries](../../index.md)/[Cube](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)(size: [Size](../../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187) = Size(2.0f), center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) = Position(0.0f)) : [Geometry.Builder](../../-geometry/-builder/index.md)

Creates a [Geometry](../../-geometry/index.md) in the shape of a cube with the give specifications.

## Parameters

androidJvm

| | |
|---|---|
| size | the size of the constructed cube |
| center | the center of the constructed cube |

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [androidJvm]<br>fun [Builder](-builder.md)(size: [Size](../../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187) = Size(2.0f), center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) = Position(0.0f)) |

## Functions

| Name | Summary |
|---|---|
| [build](../../-geometry/-builder/build.md) | [androidJvm]<br>open fun [build](../../-geometry/-builder/build.md)(engine: Engine): [Geometry](../../-geometry/index.md)<br>fun [build](../../-geometry/-builder/build.md)(sceneView: [SceneView](../../../io.github.sceneview/-scene-view/index.md)): [Geometry](../../-geometry/index.md) |

## Properties

| Name | Summary |
|---|---|
| [submeshes](../../-geometry/-builder/submeshes.md) | [androidJvm]<br>val [submeshes](../../-geometry/-builder/submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../../-geometry/-submesh/index.md)&gt; |
| [vertices](../../-geometry/-builder/vertices.md) | [androidJvm]<br>val [vertices](../../-geometry/-builder/vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../../-geometry/-vertex/index.md)&gt; |
