//[arsceneview](../../../index.md)/[io.github.sceneview.ar.scene](../index.md)/[PlaneRenderer](index.md)/[planeRendererMode](plane-renderer-mode.md)

# planeRendererMode

[androidJvm]\
var [planeRendererMode](plane-renderer-mode.md): [PlaneRenderer.PlaneRendererMode](-plane-renderer-mode/index.md)

<pre>
Set here how tracked planes should be visualized on the screen. Two options are available,
`RENDER_ALL` and `RENDER_TOP_MOST`.
To see all tracked planes which are visible to the camera set the PlaneRendererMode to
`RENDER_ALL`. This mode eats up quite a few resources and should only be set
with care. To optimize the rendering set the mode to `RENDER_TOP_MOST`.
In that case only the top most plane visible to a camera is rendered on the screen.
Especially on weaker smartphone models this improves the overall performance.

The default mode is `RENDER_TOP_MOST`
</pre> *
