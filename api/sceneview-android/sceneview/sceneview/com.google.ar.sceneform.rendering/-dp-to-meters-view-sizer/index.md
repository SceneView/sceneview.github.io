//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[DpToMetersViewSizer](index.md)

# DpToMetersViewSizer

[androidJvm]\
open class [DpToMetersViewSizer](index.md) : [ViewSizer](../-view-sizer/index.md)

Controls the size of a [ViewRenderable](../-view-renderable/index.md) in a com.google.ar.sceneform.Scene by defining how many dp (density-independent pixels) there are per meter. This is recommended when using an android layout that is built using dp.

## See also

androidJvm

| | |
|---|---|
| [com.google.ar.sceneform.rendering.ViewRenderable.Builder](../-view-renderable/-builder/set-sizer.md) |  |
| [com.google.ar.sceneform.rendering.ViewRenderable](../-view-renderable/set-sizer.md) |  |

## Constructors

| | |
|---|---|
| [DpToMetersViewSizer](-dp-to-meters-view-sizer.md) | [androidJvm]<br>open fun [DpToMetersViewSizer](-dp-to-meters-view-sizer.md)(dpPerMeters: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor for creating a sizer for controlling the size of a [ViewRenderable](../-view-renderable/index.md) by defining how many dp there are per meter. |

## Functions

| Name | Summary |
|---|---|
| [getSize](get-size.md) | [androidJvm]<br>open fun [getSize](get-size.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)<br>Calculates the desired size of the view in the com.google.ar.sceneform. |

## Properties

| Name | Summary |
|---|---|
| [dpPerMeters](dp-per-meters.md) | [androidJvm]<br>val [dpPerMeters](dp-per-meters.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
