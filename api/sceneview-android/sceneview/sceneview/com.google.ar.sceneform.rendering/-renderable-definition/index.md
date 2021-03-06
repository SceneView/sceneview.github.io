//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[RenderableDefinition](index.md)

# RenderableDefinition

[androidJvm]\
open class [RenderableDefinition](index.md)

Represents the visual information of a [Renderable](../-renderable/index.md). Can be used to construct and modify renderables dynamically.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.rendering.ModelRenderable.Builder](../-model-renderable/-builder/index.md) |  |
| [com.google.ar.sceneform.rendering.ViewRenderable.Builder](../-view-renderable/-builder/index.md) |  |

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md)<br>Factory class for [RenderableDefinition](index.md). |
| [Submesh](-submesh/index.md) | [androidJvm]<br>open class [Submesh](-submesh/index.md)<br>Represents a Submesh for a RenderableDefinition. |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [RenderableDefinition.Builder](-builder/index.md) |

## Properties

| Name | Summary |
|---|---|
| [submeshes](submeshes.md) | [androidJvm]<br>private open var [submeshes](submeshes.md): [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[RenderableDefinition.Submesh](-submesh/index.md)&gt; |
| [vertices](vertices.md) | [androidJvm]<br>private open var [vertices](vertices.md): [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[Vertex](../-vertex/index.md)&gt; |
