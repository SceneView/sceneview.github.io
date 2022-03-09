//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[FixedHeightViewSizer](index.md)

# FixedHeightViewSizer

[androidJvm]\
open class [FixedHeightViewSizer](index.md) : [ViewSizer](../-view-sizer/index.md)

Controls the size of a [ViewRenderable](../-view-renderable/index.md) in a com.google.ar.sceneform.Scene by defining how tall it should be in meters. The width will change to match the aspect ratio of the view.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.rendering.ViewRenderable.Builder](../-view-renderable/-builder/set-sizer.md) |  |
| [com.google.ar.sceneform.rendering.ViewRenderable](../-view-renderable/set-sizer.md) |  |

## Constructors

| | |
|---|---|
| [FixedHeightViewSizer](-fixed-height-view-sizer.md) | [androidJvm]<br>open fun [FixedHeightViewSizer](-fixed-height-view-sizer.md)(heightMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Constructor for creating a sizer for controlling the size of a [ViewRenderable](../-view-renderable/index.md) by defining a fixed height. |

## Functions

| Name | Summary |
|---|---|
| [getHeight](get-height.md) | [androidJvm]<br>open fun [getHeight](get-height.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Returns the height in meters used for controlling the size of a [ViewRenderable](../-view-renderable/index.md). |
| [getSize](get-size.md) | [androidJvm]<br>open fun [getSize](get-size.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Calculates the desired size of the view in the com.google.ar.sceneform. |
