//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.components](../index.md)/[CameraComponent](index.md)/[setShift](set-shift.md)

# setShift

[androidJvm]\
open fun [setShift](set-shift.md)(xShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), yShift: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Sets an additional matrix that shifts (translates) the projection matrix.

The shift parameters are specified in NDC coordinates, that is, if the translation must be specified in pixels, the xshift and yshift parameters be scaled by 1.0 / viewport.width and 1.0 / viewport.height respectively.

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.Camera |  |

## Parameters

androidJvm

| | |
|---|---|
| xShift | horizontal shift in NDC coordinates applied after the projection |
| yShift | vertical shift in NDC coordinates applied after the projection |
