//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[modelTransform](model-transform.md)

# modelTransform

[androidJvm]\
open var [modelTransform](model-transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623)

The camera's model matrix.

Helper method to set the camera's entity transform component.

The model matrix encodes the camera position and orientation, or pose.

Remember that the Camera &quot;looks&quot; towards its -z axis.

This has the same effect as calling:

```kotlin
engine.getTransformManager().setTransform(
engine.getTransformManager().getInstance(camera->getEntity()), viewMatrix);
```

Transform containing the camera's pose as a column-major matrix. The camera position and orientation provided as a **rigid transform** matrix.
