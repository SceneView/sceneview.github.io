//[sceneview](../../index.md)/[io.github.sceneview.scene](index.md)/[projectionMatrix](projection-matrix.md)

# projectionMatrix

[androidJvm]\
val Camera.[projectionMatrix](projection-matrix.md): Mat4

The camera's projection matrix

The projection matrix used for rendering always has its far plane set to infinity. This is why it may differ from the matrix set through setProjection() or setLensProjection().
