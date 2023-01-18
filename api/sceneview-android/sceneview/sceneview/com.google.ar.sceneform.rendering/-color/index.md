//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Color](index.md)

# Color

[androidJvm]\
open class [Color](index.md)

An RGBA color. Each component is a value with a range from 0 to 1. Can be created from an Android ColorInt.

#### Deprecated

## Constructors

| | |
|---|---|
| [Color](-color.md) | [androidJvm]<br>open fun [Color](-color.md)()<br>Construct a Color and default it to white (1, 1, 1, 1). |
| [Color](-color.md) | [androidJvm]<br>open fun [Color](-color.md)(color: [Color](index.md))<br>Construct a Color with the values of another color. |
| [Color](-color.md) | [androidJvm]<br>open fun [Color](-color.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Construct a color with the RGB values passed in and an alpha of 1. |
| [Color](-color.md) | [androidJvm]<br>open fun [Color](-color.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Construct a color with the RGBA values passed in. |
| [Color](-color.md) | [androidJvm]<br>open fun [Color](-color.md)(@[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)argb: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Construct a color with an integer in the sRGB color space packed as an ARGB value. |

## Functions

| Name | Summary |
|---|---|
| [inverseTonemap](inverse-tonemap.md) | [androidJvm]<br>open fun [inverseTonemap](inverse-tonemap.md)(): [Color](index.md)<br>Returns a new color with Sceneform's tonemapping inversed. |
| [set](set.md) | [androidJvm]<br>open fun [set](set.md)(color: [Color](index.md))<br>Set to the values of another color.<br>[androidJvm]<br>open fun [set](set.md)(@[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)argb: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Set to RGBA values from an integer in the sRGB color space packed as an ARGB value.<br>[androidJvm]<br>open fun [set](set.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Set to the RGB values passed in and an alpha of 1.<br>[androidJvm]<br>open fun [set](set.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Set to the RGBA values passed in. |

## Properties

| Name | Summary |
|---|---|
| [a](a.md) | [androidJvm]<br>open var [a](a.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [b](b.md) | [androidJvm]<br>open var [b](b.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [g](g.md) | [androidJvm]<br>open var [g](g.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [r](r.md) | [androidJvm]<br>open var [r](r.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
