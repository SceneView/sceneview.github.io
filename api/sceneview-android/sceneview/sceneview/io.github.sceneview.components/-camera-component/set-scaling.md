//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[setScaling](set-scaling.md)

# setScaling

[androidJvm]\
open fun [setScaling](set-scaling.md)(scaling: Float2)

Sets an additional matrix that scales the projection matrix.

This is useful to adjust the aspect ratio of the camera independent from its projection. First, pass an aspect of 1.0 to setProjection. Then set the scaling with the desired aspect ratio:

```kotlin
double aspect = width / height;

// with Fov.HORIZONTAL passed to setProjection:
camera.setScaling(1.0, aspect);

// with Fov.VERTICAL passed to setProjection:
camera.setScaling(1.0 / aspect, 1.0);
```

By default, this is an identity matrix.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.Camera |  |

## Parameters

androidJvm

| | |
|---|---|
| scaling | horizontal and vertical scaling to be applied after the projection matrix. |
