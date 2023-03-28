//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.geometries](../index.md)/[Geometry](index.md)

# Geometry

[androidJvm]\
open class [Geometry](index.md)(val vertexBuffer: VertexBuffer, val indexBuffer: IndexBuffer)

Geometry parameters for building and updating a Renderable

A renderable is made of several primitives. You can ever declare only 1 if you want each parts of your Geometry to have the same material or one for each triangle indices with a different material. We could declare n primitives (n per face) and give each of them a different material instance, setup with different parameters

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.geometries.Cube](../-cube/index.md) |  |
| [io.github.sceneview.geometries.Cylinder](../-cylinder/index.md) |  |
| [io.github.sceneview.geometries.Plane](../-plane/index.md) |  |
| [io.github.sceneview.geometries.Sphere](../-sphere/index.md) |  |

## Constructors

| | |
|---|---|
| [Geometry](-geometry.md) | [androidJvm]<br>fun [Geometry](-geometry.md)(vertexBuffer: VertexBuffer, indexBuffer: IndexBuffer) |

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>open class [Builder](-builder/index.md)(val vertices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-vertex/index.md)&gt;, val submeshes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](-submesh/index.md)&gt;) |
| [Submesh](-submesh/index.md) | [androidJvm]<br>data class [Submesh](-submesh/index.md)(val triangleIndices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;)<br>Represents a Submesh for a Geometry. |
| [Vertex](-vertex/index.md) | [androidJvm]<br>data class [Vertex](-vertex/index.md)(val position: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) = Position(), val normal: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-602047187)? = null, val uvCoordinate: [UvCoordinate](../index.md#661897273%2FClasslikes%2F-602047187)? = null, val color: [Color](../../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-602047187)? = null)<br>Used for constructing renderables dynamically |

## Functions

| Name | Summary |
|---|---|
| [setBufferIndices](set-buffer-indices.md) | [androidJvm]<br>fun [setBufferIndices](set-buffer-indices.md)(engine: Engine, submeshes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](-submesh/index.md)&gt;) |
| [setBufferVertices](set-buffer-vertices.md) | [androidJvm]<br>fun [setBufferVertices](set-buffer-vertices.md)(engine: Engine, vertices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-vertex/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [boundingBox](bounding-box.md) | [androidJvm]<br>lateinit var [boundingBox](bounding-box.md): Box |
| [indexBuffer](index-buffer.md) | [androidJvm]<br>val [indexBuffer](index-buffer.md): IndexBuffer |
| [offsetsCounts](offsets-counts.md) | [androidJvm]<br>lateinit var [offsetsCounts](offsets-counts.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt; |
| [submeshes](submeshes.md) | [androidJvm]<br>lateinit var [submeshes](submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](-submesh/index.md)&gt; |
| [vertexBuffer](vertex-buffer.md) | [androidJvm]<br>val [vertexBuffer](vertex-buffer.md): VertexBuffer |
| [vertices](vertices.md) | [androidJvm]<br>lateinit var [vertices](vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-vertex/index.md)&gt; |

## Inheritors

| Name |
|---|
| [Plane](../-plane/index.md) |
