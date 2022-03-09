//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Light](index.md)

# Light

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

open class [Light](index.md)

Light property store.

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md)<br>Factory class for [Light](index.md) |
| [Type](-type/index.md) | [androidJvm]<br>enum [Type](-type/index.md)<br>Type of Light Source |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(type: [Light.Type](-type/index.md)): [Light.Builder](-builder/index.md)<br>Constructs a default light, if nothing else is set |
| [createInstance](create-instance.md) | [androidJvm]<br>open fun [createInstance](create-instance.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)): [LightInstance](../-light-instance/index.md) |
| [getInnerConeAngle](get-inner-cone-angle.md) | [androidJvm]<br>open fun [getInnerConeAngle](get-inner-cone-angle.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the inner cone angle for spotlights. |
| [getLocalDirection](get-local-direction.md) | [androidJvm]<br>open fun [getLocalDirection](get-local-direction.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getLocalPosition](get-local-position.md) | [androidJvm]<br>open fun [getLocalPosition](get-local-position.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getOuterConeAngle](get-outer-cone-angle.md) | [androidJvm]<br>open fun [getOuterConeAngle](get-outer-cone-angle.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Get the outer cone angle for spotlights. |
| [isShadowCastingEnabled](is-shadow-casting-enabled.md) | [androidJvm]<br>open fun [isShadowCastingEnabled](is-shadow-casting-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if the light has shadow casting enabled. |
| [setColorTemperature](set-color-temperature.md) | [androidJvm]<br>open fun [setColorTemperature](set-color-temperature.md)(temperature: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Sets the "RGB" color of the light based on the desired "color temperature. |
| [setInnerConeAngle](set-inner-cone-angle.md) | [androidJvm]<br>open fun [setInnerConeAngle](set-inner-cone-angle.md)(coneInner: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Spotlights shine light in a cone, this value determines the size of the inner part of the cone. |
| [setOuterConeAngle](set-outer-cone-angle.md) | [androidJvm]<br>open fun [setOuterConeAngle](set-outer-cone-angle.md)(coneOuter: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Spotlights shine light in a cone, this value determines the size of the outer part of the cone. |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>private var [color](color.md): [Color](../-color/index.md) |
| [falloffRadius](falloff-radius.md) | [androidJvm]<br>private open var [falloffRadius](falloff-radius.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [intensity](intensity.md) | [androidJvm]<br>private open var [intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [type](type.md) | [androidJvm]<br>private val [type](type.md): [Light.Type](-type/index.md) |
