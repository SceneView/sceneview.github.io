//[sceneview](../../../../index.md)/[io.github.sceneview.geometries](../../index.md)/[Plane](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)(val center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(0.0f), val size: [Size](../../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623) = Size(x = 2.0f, y = 2.0f), val normal: [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) = Direction(y = 1.0f)) : [Geometry.Builder](../../-geometry/-builder/index.md)

Creates a [Geometry](../../-geometry/index.md) in the shape of a plane with the give specifications

## Parameters

androidJvm

| | |
|---|---|
| center | Center of the constructed plane |
| size | Size of the constructed plane |
| normal | Looking at direction |

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [androidJvm]<br>fun [Builder](-builder.md)(center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(0.0f), size: [Size](../../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623) = Size(x = 2.0f, y = 2.0f), normal: [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) = Direction(y = 1.0f)) |

## Functions

| Name | Summary |
|---|---|
| [build](../../-geometry/-builder/build.md) | [androidJvm]<br>fun [build](../../-geometry/-builder/build.md)(sceneView: [SceneView](../../../io.github.sceneview/-scene-view/index.md)): [Geometry](../../-geometry/index.md)<br>open override fun [build](build.md)(engine: Engine): [Plane](../index.md) |

## Properties

| Name | Summary |
|---|---|
| [center](center.md) | [androidJvm]<br>val [center](center.md): [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) |
| [normal](normal.md) | [androidJvm]<br>val [normal](normal.md): [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) |
| [size](size.md) | [androidJvm]<br>val [size](size.md): [Size](../../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-1571379623) |
| [submeshes](../../-geometry/-builder/submeshes.md) | [androidJvm]<br>val [submeshes](../../-geometry/-builder/submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../../-geometry/-submesh/index.md)&gt; |
| [vertices](../../-geometry/-builder/vertices.md) | [androidJvm]<br>val [vertices](../../-geometry/-builder/vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../../-geometry/-vertex/index.md)&gt; |
