//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.managers](index.md)/[geometry](geometry.md)

# geometry

[androidJvm]\
fun RenderableManager.Builder.[geometry](geometry.md)(geometry: [Geometry](../io.github.sceneview.geometries/-geometry/index.md)): RenderableManager.Builder

Specifies the geometry data for a primitive.

Filament primitives must have an associated VertexBuffer and IndexBuffer. Typically, each primitive is specified with a pair of daisy-chained calls: [geometry](geometry.md) and RenderableManager.Builder.material.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.geometries.Geometry](../io.github.sceneview.geometries/-geometry/index.md) |  |
| [io.github.sceneview.geometries.Plane](../io.github.sceneview.geometries/-plane/index.md) |  |
| [io.github.sceneview.geometries.Cube](../io.github.sceneview.geometries/-cube/index.md) |  |
| [io.github.sceneview.geometries.Sphere](../io.github.sceneview.geometries/-sphere/index.md) |  |
| [io.github.sceneview.geometries.Cylinder](../io.github.sceneview.geometries/-cylinder/index.md) |  |
| [RenderableManager.setGeometry](set-geometry.md) |  |
