//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Vertex](index.md)

# Vertex

[androidJvm]\
open class [Vertex](index.md)

Represents a Vertex for a [RenderableDefinition](../-renderable-definition/index.md). Used for constructing renderables dynamically.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.rendering.ModelRenderable.Builder](../-model-renderable/-builder/index.md) |  |
| [com.google.ar.sceneform.rendering.ViewRenderable.Builder](../-view-renderable/-builder/index.md) |  |

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md)<br>Factory class for [Vertex](index.md). |
| [UvCoordinate](-uv-coordinate/index.md) | [androidJvm]<br>class [UvCoordinate](-uv-coordinate/index.md)<br>Represents a texture Coordinate for a Vertex. |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [Vertex.Builder](-builder/index.md) |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [color](color.md): [Color](../-color/index.md) |
| [normal](normal.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [normal](normal.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [position](position.md) | [androidJvm]<br>private var [position](position.md): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [uvCoordinate](uv-coordinate.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [uvCoordinate](uv-coordinate.md): [Vertex.UvCoordinate](-uv-coordinate/index.md) |
