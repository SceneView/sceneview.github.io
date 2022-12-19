//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[skybox](skybox.md)

# skybox

[androidJvm]\
var [skybox](skybox.md): Skybox?

The Skybox is drawn last and covers all pixels not touched by geometry

The skybox texture is rendered as though it were an infinitely large cube with the camera inside it. This means that the cubemap which is mapped onto the cube's exterior will appear mirrored. This follows the OpenGL conventions.

When added to a [SceneView](index.md), the `Skybox` fills all untouched pixels.

Set to null to unset the Skybox.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.utils.HDRLoader |  |
| com.google.android.filament.utils.KTX1Loader |  |
| com.google.android.filament.Scene |  |
