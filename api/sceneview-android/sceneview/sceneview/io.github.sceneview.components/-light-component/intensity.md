//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[LightComponent](index.md)/[intensity](intensity.md)

# intensity

[androidJvm]\
open var [intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

Dynamically updates the light's intensity

The intensity can be negative.

This parameter depends on the LightManager.Type, for directional lights, it specifies the illuminance in <i>lux</i> (or <i>lumen/m^2</i>). For point lights and spot lights, it specifies the luminous power in <i>lumen</i>. For example, the sun's illuminance is about 100,000 lux.

This method is equivalent to calling setIntensity for directional lights (LightManager.Type.DIRECTIONAL or LightManager.Type.SUN).

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.LightManager |  |
