//[sceneview](../../index.md)/[io.github.sceneview.light](index.md)

# Package io.github.sceneview.light

## Types

| Name | Summary |
|---|---|
| [Light](index.md#1927638868%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Light](index.md#1927638868%2FClasslikes%2F-1571379623) = [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [LightInstance](index.md#1549101375%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [LightInstance](index.md#1549101375%2FClasslikes%2F-1571379623) = [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun IndirectLight.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): IndirectLight<br>fun LightManager.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [Light](index.md#1927638868%2FClasslikes%2F-1571379623) |
| [clone](clone.md) | [androidJvm]<br>fun [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[clone](clone.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [destroy](destroy.md) | [androidJvm]<br>fun IndirectLight.[destroy](destroy.md)()<br>Destroys an IndirectLight and frees all its associated resources.<br>[androidJvm]<br>fun [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[destroy](destroy.md)()<br>Destroys a Light and frees all its associated resources. |

## Properties

| Name | Summary |
|---|---|
| [color](color.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[color](color.md): [Color](../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623) |
| [direction](direction.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[direction](direction.md): [Direction](../io.github.sceneview.math/index.md#1758682841%2FClasslikes%2F-1571379623) |
| [falloff](falloff.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[falloff](falloff.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [innerConeAngle](inner-cone-angle.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[innerConeAngle](inner-cone-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [instance](instance.md) | [androidJvm]<br>val [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[instance](instance.md): [LightInstance](index.md#1549101375%2FClasslikes%2F-1571379623) |
| [intensity](intensity.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[intensity](intensity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [isShadowCaster](is-shadow-caster.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[isShadowCaster](is-shadow-caster.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [outerConeAngle](outer-cone-angle.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[outerConeAngle](outer-cone-angle.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [position](position.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[position](position.md): [Position](../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) |
| [sunAngularRadius](sun-angular-radius.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[sunAngularRadius](sun-angular-radius.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [sunHaloFalloff](sun-halo-falloff.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[sunHaloFalloff](sun-halo-falloff.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [sunHaloSize](sun-halo-size.md) | [androidJvm]<br>var [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[sunHaloSize](sun-halo-size.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [type](type.md) | [androidJvm]<br>val [Light](index.md#1927638868%2FClasslikes%2F-1571379623).[type](type.md): LightManager.Type |
