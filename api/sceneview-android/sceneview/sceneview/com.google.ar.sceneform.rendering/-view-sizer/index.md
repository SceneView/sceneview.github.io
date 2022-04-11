//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ViewSizer](index.md)

# ViewSizer

[androidJvm]\
interface [ViewSizer](index.md)

Interface for controlling the size of a [ViewRenderable](../-view-renderable/index.md) in the . The final size that the view is displayed at will be the size from this [ViewSizer](index.md) scaled by the getWorldScale of the com.google.ar.sceneform.Node that the [ViewRenderable](../-view-renderable/index.md) is attached to.

## Functions

| Name | Summary |
|---|---|
| [getSize](get-size.md) | [androidJvm]<br>abstract fun [getSize](get-size.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Calculates the desired size of the view in the com.google.ar.sceneform. |

## Inheritors

| Name |
|---|
| [FixedHeightViewSizer](../-fixed-height-view-sizer/index.md) |
| [FixedWidthViewSizer](../-fixed-width-view-sizer/index.md) |
| [DpToMetersViewSizer](../-dp-to-meters-view-sizer/index.md) |
