//[sceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Camera](index.md)/[worldToScreenPoint](world-to-screen-point.md)

# worldToScreenPoint

[androidJvm]\
open fun [worldToScreenPoint](world-to-screen-point.md)(point: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)

Convert a point from world space into screen space. 

The X value is negative when the point is left of the viewport, between 0 and the width of the [SceneView](../../io.github.sceneview/-scene-view/index.md) when the point is within the viewport, and greater than the width when the point is to the right of the viewport. 

The Y value is negative when the point is below the viewport, between 0 and the height of the [SceneView](../../io.github.sceneview/-scene-view/index.md) when the point is within the viewport, and greater than the height when the point is above the viewport. 

The Z value is always 0 since the return value is a 2D coordinate.

#### Return

a new vector that represents the point in screen-space.

## Parameters

androidJvm

| | |
|---|---|
| point | the point in world space to convert |
