//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.geometries](../index.md)/[Plane](index.md)

# Plane

[androidJvm]\
class [Plane](index.md) : [Geometry](../-geometry/index.md)

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md)(val center: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) = Position(0.0f), val size: [Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187) = Size(x = 2.0f, y = 2.0f), val normal: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-602047187) = Direction(y = 1.0f)) : [Geometry.Builder](../-geometry/-builder/index.md)<br>Creates a [Geometry](../-geometry/index.md) in the shape of a plane with the give specifications |
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [setBufferIndices](../-geometry/set-buffer-indices.md) | [androidJvm]<br>fun [setBufferIndices](../-geometry/set-buffer-indices.md)(engine: Engine, submeshes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../-geometry/-submesh/index.md)&gt;) |
| [setBufferVertices](../-geometry/set-buffer-vertices.md) | [androidJvm]<br>fun [setBufferVertices](../-geometry/set-buffer-vertices.md)(engine: Engine, vertices: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../-geometry/-vertex/index.md)&gt;) |
| [update](update.md) | [androidJvm]<br>fun [update](update.md)(engine: Engine, center: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187) = this.center, size: [Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187) = this.size, normal: [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-602047187) = this.normal) |

## Properties

| Name | Summary |
|---|---|
| [boundingBox](../-geometry/bounding-box.md) | [androidJvm]<br>lateinit var [boundingBox](../-geometry/bounding-box.md): Box |
| [center](center.md) | [androidJvm]<br>var [center](center.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)<br>Center of the constructed plane |
| [indexBuffer](../-geometry/index-buffer.md) | [androidJvm]<br>val [indexBuffer](../-geometry/index-buffer.md): IndexBuffer |
| [normal](normal.md) | [androidJvm]<br>var [normal](normal.md): [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-602047187)<br>Looking at direction |
| [offsetsCounts](../-geometry/offsets-counts.md) | [androidJvm]<br>lateinit var [offsetsCounts](../-geometry/offsets-counts.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;&gt; |
| [size](size.md) | [androidJvm]<br>var [size](size.md): [Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187)<br>Size of the constructed plane |
| [submeshes](../-geometry/submeshes.md) | [androidJvm]<br>lateinit var [submeshes](../-geometry/submeshes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Submesh](../-geometry/-submesh/index.md)&gt; |
| [vertexBuffer](../-geometry/vertex-buffer.md) | [androidJvm]<br>val [vertexBuffer](../-geometry/vertex-buffer.md): VertexBuffer |
| [vertices](../-geometry/vertices.md) | [androidJvm]<br>lateinit var [vertices](../-geometry/vertices.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](../-geometry/-vertex/index.md)&gt; |
