//[sceneview](../../../../index.md)/[io.github.sceneview.geometries](../../index.md)/[Cylinder](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)(radius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f, height: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f, center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(0.0f), sideCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 24) : [Geometry.Builder](../../-geometry/-builder/index.md)

Creates a [Geometry](../../-geometry/index.md) in the shape of a cylinder with the give specifications.

## Parameters

androidJvm

| | |
|---|---|
| radius | the radius of the constructed cylinder |
| height | the height of the constructed cylinder |
| center | the center of the constructed cylinder |

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [androidJvm]<br>fun [Builder](-builder.md)(radius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f, height: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f, center: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(0.0f), sideCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 24) |

## Functions

| Name | Summary |
|---|---|
| [build](../../-geometry/-builder/build.md) | [androidJvm]<br>open fun [build](../../-geometry/-builder/build.md)(engine: Engine): [Geometry](../../-geometry/index.md)<br>fun [build](../../-geometry/-builder/build.md)(sceneView: [SceneView](../../../io.github.sceneview/-scene-view/index.md)): [Geometry](../../-geometry/index.md) |

## Properties

| Name | Summary |
|---|---|
| [submeshes](../../-geometry/-builder/submeshes.md) | [androidJvm]<br>val [submeshes](../../-geometry/-builder/submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../../-geometry/-submesh/index.md)&gt; |
| [vertices](../../-geometry/-builder/vertices.md) | [androidJvm]<br>val [vertices](../../-geometry/-builder/vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../../-geometry/-vertex/index.md)&gt; |
