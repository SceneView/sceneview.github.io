//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Light](../index.md)/[Type](index.md)

# Type

[androidJvm]\
enum [Type](index.md)

Type of Light Source

## Entries

| | |
|---|---|
| [POINT](-p-o-i-n-t/index.md) | [androidJvm]<br>[POINT](-p-o-i-n-t/index.md)<br>Approximates light radiating in all directions from a single point in space, where the intensity falls off with the inverse square of the distance. Point lights have a position but no direction. Use [setFalloffRadius](../../../../../arsceneview/com.google.ar.sceneform.rendering/-light/set-falloff-radius.md) to control the falloff. |
| [DIRECTIONAL](-d-i-r-e-c-t-i-o-n-a-l/index.md) | [androidJvm]<br>[DIRECTIONAL](-d-i-r-e-c-t-i-o-n-a-l/index.md)<br>Approximates an infinitely far away, purely directional light |
| [SPOTLIGHT](-s-p-o-t-l-i-g-h-t/index.md) | [androidJvm]<br>[SPOTLIGHT](-s-p-o-t-l-i-g-h-t/index.md)<br>Similar to a point light but radiating light in a cone rather than all directions. Note that as you make the cone wider, the energy is spread causing the lighting to appear dimmer. A spotlight has a position and a direction. Use [setInnerConeAngle](../set-inner-cone-angle.md) and [setOuterConeAngle](../set-outer-cone-angle.md) to control the cone size. |
| [FOCUSED_SPOTLIGHT](-f-o-c-u-s-e-d_-s-p-o-t-l-i-g-h-t/index.md) | [androidJvm]<br>[FOCUSED_SPOTLIGHT](-f-o-c-u-s-e-d_-s-p-o-t-l-i-g-h-t/index.md)<br>The same as a spotlight with the exception that the apparent lighting stays the same as the cone angle changes. A spotlight has a position and a direction. Use [setInnerConeAngle](../set-inner-cone-angle.md) and [setOuterConeAngle](../set-outer-cone-angle.md) to control the cone size. |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>open fun [valueOf](value-of.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Light.Type](index.md) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Light.Type](index.md)&gt; |
