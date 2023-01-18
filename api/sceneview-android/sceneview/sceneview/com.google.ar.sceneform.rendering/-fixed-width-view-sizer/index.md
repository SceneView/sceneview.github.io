//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[FixedWidthViewSizer](index.md)

# FixedWidthViewSizer

[androidJvm]\
open class [FixedWidthViewSizer](index.md) : [ViewSizer](../-view-sizer/index.md)

Controls the size of a [ViewRenderable](../-view-renderable/index.md) in a com.google.ar.sceneform.Scene by defining how wide it should be in meters. The height will change to match the aspect ratio of the view.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.rendering.ViewRenderable.Builder](../-view-renderable/-builder/set-sizer.md) |  |
| [com.google.ar.sceneform.rendering.ViewRenderable](../-view-renderable/set-sizer.md) |  |

## Constructors

| | |
|---|---|
| [FixedWidthViewSizer](-fixed-width-view-sizer.md) | [androidJvm]<br>open fun [FixedWidthViewSizer](-fixed-width-view-sizer.md)(widthMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Constructor for creating a sizer for controlling the size of a [ViewRenderable](../-view-renderable/index.md) by defining a fixed width. |

## Functions

| Name | Summary |
|---|---|
| [getSize](get-size.md) | [androidJvm]<br>open fun [getSize](get-size.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Calculates the desired size of the view in the com.google.ar.sceneform. |
| [getWidth](get-width.md) | [androidJvm]<br>open fun [getWidth](get-width.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Returns the width in meters used for controlling the size of a [ViewRenderable](../-view-renderable/index.md). |
