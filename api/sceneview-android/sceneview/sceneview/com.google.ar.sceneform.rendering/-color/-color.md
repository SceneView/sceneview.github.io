//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Color](index.md)/[Color](-color.md)

# Color

[androidJvm]\
open fun [Color](-color.md)()

Construct a Color and default it to white (1, 1, 1, 1).

[androidJvm]\
open fun [Color](-color.md)(color: [Color](index.md))

Construct a Color with the values of another color.

[androidJvm]\
open fun [Color](-color.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Construct a color with the RGB values passed in and an alpha of 1.

[androidJvm]\
open fun [Color](-color.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Construct a color with the RGBA values passed in.

[androidJvm]\
open fun [Color](-color.md)(@[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)argb: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Construct a color with an integer in the sRGB color space packed as an ARGB value. Used for constructing from an Android ColorInt.
