//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[LightComponent](index.md)

# LightComponent

[androidJvm]\
interface [LightComponent](index.md) : [Component](../-component/index.md)

## Functions

| Name | Summary |
|---|---|
| [getLightChannel](get-light-channel.md) | [androidJvm]<br>open fun [getLightChannel](get-light-channel.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 7)channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether a light channel is enabled on a specified renderable. |
| [setIntensity](set-intensity.md) | [androidJvm]<br>open fun [setIntensity](set-intensity.md)(watts: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), efficiency: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Dynamically updates the light's intensity. The intensity can be negative. |
| [setIntensityCandela](set-intensity-candela.md) | [androidJvm]<br>open fun [setIntensityCandela](set-intensity-candela.md)(intensity: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Dynamically updates the light's intensity in candela. The intensity can be negative. |
| [setLightChannel](set-light-channel.md) | [androidJvm]<br>open fun [setLightChannel](set-light-channel.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 7)channel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), enable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Enables or disables a light channel. Light channel 0 is enabled by default. |
| [setSpotLightCone](set-spot-light-cone.md) | [androidJvm]<br>open fun [setSpotLightCone](set-spot-light-cone.md)(inner: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), outer: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))<br>Dynamically updates a spot light's cone as angles |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>open var [color](color.md): [Color](../../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)<br>Dynamically updates the light's hue as linear sRGB |
| [engine](../-component/engine.md) | [androidJvm]<br>abstract val [engine](../-component/engine.md): Engine |
| [entity](../-component/entity.md) | [androidJvm]<br>abstract val [entity](../-component/entity.md): [Entity](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623) |
| [falloff](falloff.md) | [androidJvm]<br>open var [falloff](falloff.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>The falloff distance for point lights and spot lights. |
| [innerConeAngle](inner-cone-angle.md) | [androidJvm]<br>open val [innerConeAngle](inner-cone-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [intensity](intensity.md) | [androidJvm]<br>open var [intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Dynamically updates the light's intensity |
| [isShadowCaster](is-shadow-caster.md) | [androidJvm]<br>open var [isShadowCaster](is-shadow-caster.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether this Light casts shadows (disabled by default) |
| [lightDirection](light-direction.md) | [androidJvm]<br>open var [lightDirection](light-direction.md): [Direction](../../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623)<br>The light's direction in world space |
| [lightInstance](light-instance.md) | [androidJvm]<br>open val [lightInstance](light-instance.md): [EntityInstance](../index.md#-275222848%2FClasslikes%2F-1571379623) |
| [lightManager](light-manager.md) | [androidJvm]<br>open val [lightManager](light-manager.md): LightManager |
| [lightPosition](light-position.md) | [androidJvm]<br>open var [lightPosition](light-position.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)<br>The light's position in world space |
| [lightQuaternion](light-quaternion.md) | [androidJvm]<br>open var [lightQuaternion](light-quaternion.md): Quaternion<br>The light's rotation in world space |
| [outerConeAngle](outer-cone-angle.md) | [androidJvm]<br>open val [outerConeAngle](outer-cone-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [sunAngularRadius](sun-angular-radius.md) | [androidJvm]<br>open var [sunAngularRadius](sun-angular-radius.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Dynamically updates the angular radius of a Type.SUN light. |
| [sunHaloFalloff](sun-halo-falloff.md) | [androidJvm]<br>open var [sunHaloFalloff](sun-halo-falloff.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Dynamically updates the halo falloff of a Type.SUN light. |
| [sunHaloSize](sun-halo-size.md) | [androidJvm]<br>open var [sunHaloSize](sun-halo-size.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Dynamically updates the halo radius of a Type.SUN light |
| [type](type.md) | [androidJvm]<br>open val [type](type.md): LightManager.Type |

## Inheritors

| Name |
|---|
| [LightNode](../../io.github.sceneview.nodes/-light-node/index.md) |
| [LightNode](../../io.github.sceneview.nodes/-model-node/-light-node/index.md) |
