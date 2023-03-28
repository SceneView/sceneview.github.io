//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.geometries](../../index.md)/[Geometry](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
open class [Builder](index.md)(val vertices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../-vertex/index.md)&gt;, val submeshes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../-submesh/index.md)&gt;)

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [androidJvm]<br>fun [Builder](-builder.md)(vertices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../-vertex/index.md)&gt;, submeshes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../-submesh/index.md)&gt;) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(engine: Engine): [Geometry](../index.md)<br>fun [build](build.md)(sceneView: [SceneView](../../../io.github.sceneview/-scene-view/index.md)): [Geometry](../index.md) |

## Properties

| Name | Summary |
|---|---|
| [submeshes](submeshes.md) | [androidJvm]<br>val [submeshes](submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../-submesh/index.md)&gt; |
| [vertices](vertices.md) | [androidJvm]<br>val [vertices](vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../-vertex/index.md)&gt; |

## Inheritors

| Name |
|---|
| [Builder](../../-cube/-builder/index.md) |
| [Builder](../../-cylinder/-builder/index.md) |
| [Builder](../../-plane/-builder/index.md) |
| [Builder](../../-sphere/-builder/index.md) |
