//[sceneview](../../../../index.md)/[io.github.sceneview.geometries](../../index.md)/[Geometry](../index.md)/[Vertex](index.md)

# Vertex

[androidJvm]\
data class [Vertex](index.md)(val position: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(), val normal: [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)? = null, val uvCoordinate: [UvCoordinate](../../index.md#661897273%2FClasslikes%2F-1571379623)? = null, val color: [Color](../../../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)? = null)

Used for constructing renderables dynamically

## Parameters

androidJvm

| | |
|---|---|
| uvCoordinate | Represents a texture Coordinate for a Vertex. Values should be between 0 and 1. |

## Constructors

| | |
|---|---|
| [Vertex](-vertex.md) | [androidJvm]<br>fun [Vertex](-vertex.md)(position: [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(), normal: [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)? = null, uvCoordinate: [UvCoordinate](../../index.md#661897273%2FClasslikes%2F-1571379623)? = null, color: [Color](../../../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)? = null) |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>val [color](color.md): [Color](../../../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)? = null |
| [normal](normal.md) | [androidJvm]<br>val [normal](normal.md): [Direction](../../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)? = null |
| [position](position.md) | [androidJvm]<br>val [position](position.md): [Position](../../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) |
| [uvCoordinate](uv-coordinate.md) | [androidJvm]<br>val [uvCoordinate](uv-coordinate.md): [UvCoordinate](../../index.md#661897273%2FClasslikes%2F-1571379623)? = null |
