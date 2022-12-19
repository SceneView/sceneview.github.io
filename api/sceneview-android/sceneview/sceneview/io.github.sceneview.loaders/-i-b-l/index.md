//[sceneview](../../../index.md)/[io.github.sceneview.loaders](../index.md)/[IBL](index.md)

# IBL

[androidJvm]\
class [IBL](index.md)(val indirectLight: IndirectLight, val sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)?)

Indirect Based Light

## Constructors

| | |
|---|---|
| [IBL](-i-b-l.md) | [androidJvm]<br>fun [IBL](-i-b-l.md)(indirectLight: IndirectLight, sphericalHarmonics: [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [indirectLight](indirect-light.md) | [androidJvm]<br>val [indirectLight](indirect-light.md): IndirectLight<br>Filament texture, or null on failure. |
| [sphericalHarmonics](spherical-harmonics.md) | [androidJvm]<br>val [sphericalHarmonics](spherical-harmonics.md): [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html)?<br>Spherical harmonics from the content of a KTX file. The resulting array of 9 * 3 floats, or null on failure. |
