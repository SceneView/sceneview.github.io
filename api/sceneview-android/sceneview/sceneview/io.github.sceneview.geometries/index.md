//[sceneview](../../index.md)/[io.github.sceneview.geometries](index.md)

# Package io.github.sceneview.geometries

## Types

| Name | Summary |
|---|---|
| [Cube](-cube/index.md) | [androidJvm]<br>class [Cube](-cube/index.md) |
| [Cylinder](-cylinder/index.md) | [androidJvm]<br>class [Cylinder](-cylinder/index.md) |
| [Geometry](-geometry/index.md) | [androidJvm]<br>open class [Geometry](-geometry/index.md)(val vertexBuffer: VertexBuffer, val indexBuffer: IndexBuffer)<br>Geometry parameters for building and updating a Renderable |
| [Plane](-plane/index.md) | [androidJvm]<br>class [Plane](-plane/index.md) : [Geometry](-geometry/index.md) |
| [Sphere](-sphere/index.md) | [androidJvm]<br>class [Sphere](-sphere/index.md) |
| [UvCoordinate](index.md#661897273%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [UvCoordinate](index.md#661897273%2FClasslikes%2F-1571379623) = Float2 |

## Functions

| Name | Summary |
|---|---|
| [destroyGeometry](destroy-geometry.md) | [androidJvm]<br>fun Engine.[destroyGeometry](destroy-geometry.md)(geometry: [Geometry](-geometry/index.md))<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyGeometry](destroy-geometry.md)(geometry: [Geometry](-geometry/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [hasColors](has-colors.md) | [androidJvm]<br>val [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-geometry/-vertex/index.md)&gt;.[hasColors](has-colors.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasNormals](has-normals.md) | [androidJvm]<br>val [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-geometry/-vertex/index.md)&gt;.[hasNormals](has-normals.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasUvCoordinates](has-uv-coordinates.md) | [androidJvm]<br>val [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Geometry.Vertex](-geometry/-vertex/index.md)&gt;.[hasUvCoordinates](has-uv-coordinates.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
