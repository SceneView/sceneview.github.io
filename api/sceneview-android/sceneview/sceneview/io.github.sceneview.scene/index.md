//[sceneview](../../index.md)/[io.github.sceneview.scene](index.md)

# Package io.github.sceneview.scene

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun ColorGrading.Builder.[build](build.md)(): ColorGrading<br>fun Skybox.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): Skybox |
| [destroy](destroy.md) | [androidJvm]<br>fun Camera.[destroy](destroy.md)()<br>Destroys the Camera component associated with the camera entity.<br>[androidJvm]<br>fun Renderer.[destroy](destroy.md)()<br>fun Scene.[destroy](destroy.md)()<br>fun View.[destroy](destroy.md)()<br>[androidJvm]<br>fun Skybox.[destroy](destroy.md)()<br>Destroys a Skybox and frees all its associated resources. |
| [illuminance](illuminance.md) | [androidJvm]<br>fun Camera.[illuminance](illuminance.md)(ev100: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [luminance](luminance.md) | [androidJvm]<br>fun Camera.[luminance](luminance.md)(ev100: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |

## Properties

| Name | Summary |
|---|---|
| [ev100](ev100.md) | [androidJvm]<br>val Camera.[ev100](ev100.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Exposure value (EV) is a number that represents a combination of a camera's shutter speed and f-number, such that all combinations that yield the same exposure have the same EV (for any fixed scene luminance) |
| [exposureFactor](exposure-factor.md) | [androidJvm]<br>val Camera.[exposureFactor](exposure-factor.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Calculate a unit-less intensity scale from the actual Filament camera settings |
| [illuminance](illuminance.md) | [androidJvm]<br>val Camera.[illuminance](illuminance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [luminance](luminance.md) | [androidJvm]<br>val Camera.[luminance](luminance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
