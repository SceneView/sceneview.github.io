//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Light](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md)

Factory class for [Light](../index.md)

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(): [Light](../index.md)<br>Creates a new [Light](../index.md) based on the parameters set previously |
| [setColorTemperature](set-color-temperature.md) | [androidJvm]<br>open fun [setColorTemperature](set-color-temperature.md)(temperature: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Light.Builder](index.md)<br>Sets the "RGB" color of the light based on the desired "color temperature. |
| [setInnerConeAngle](set-inner-cone-angle.md) | [androidJvm]<br>open fun [setInnerConeAngle](set-inner-cone-angle.md)(coneInner: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Light.Builder](index.md)<br>Spotlights shine light in a cone, this value determines the size of the inner part of the cone. |
| [setOuterConeAngle](set-outer-cone-angle.md) | [androidJvm]<br>open fun [setOuterConeAngle](set-outer-cone-angle.md)(coneOuter: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Light.Builder](index.md)<br>Spotlights shine light in a cone, this value determines the size of the outer part of the cone. |
| [setShadowCastingEnabled](set-shadow-casting-enabled.md) | [androidJvm]<br>open fun [setShadowCastingEnabled](set-shadow-casting-enabled.md)(enableShadows: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Light.Builder](index.md)<br>Determines whether the light casts shadows, or whether synthetic objects can block the light. |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>private open var [color](color.md): [Color](../../-color/index.md) |
| [falloffRadius](falloff-radius.md) | [androidJvm]<br>private open var [falloffRadius](falloff-radius.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [intensity](intensity.md) | [androidJvm]<br>private open var [intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
