//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Material](index.md)

# Material

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

open class [Material](index.md)

Represents a reference to a material.

## Constructors

| | |
|---|---|
| [Material](-material.md) | [androidJvm]<br>open fun [Material](-material.md)(materialData: [MaterialInternalData](../-material-internal-data/index.md), cleanupResource: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md)<br>Builder for constructing a [Material](index.md) |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [Material.Builder](-builder/index.md)<br>Constructs a [Material](index.md) |
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |
| [getExternalTexture](get-external-texture.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getExternalTexture](get-external-texture.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [ExternalTexture](../-external-texture/index.md) |
| [getFilamentMaterialInstance](get-filament-material-instance.md) | [androidJvm]<br>open fun [getFilamentMaterialInstance](get-filament-material-instance.md)(): MaterialInstance |
| [makeCopy](make-copy.md) | [androidJvm]<br>open fun [makeCopy](make-copy.md)(): [Material](index.md)<br>Creates a new instance of this Material. |
| [setBaseColorTexture](set-base-color-texture.md) | [androidJvm]<br>open fun [setBaseColorTexture](set-base-color-texture.md)(texture: [Texture](../-texture/index.md)) |
| [setBoolean](set-boolean.md) | [androidJvm]<br>open fun [setBoolean](set-boolean.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setBoolean2](set-boolean2.md) | [androidJvm]<br>open fun [setBoolean2](set-boolean2.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), y: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setBoolean3](set-boolean3.md) | [androidJvm]<br>open fun [setBoolean3](set-boolean3.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), y: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), z: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setBoolean4](set-boolean4.md) | [androidJvm]<br>open fun [setBoolean4](set-boolean4.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), y: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), z: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), w: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setDepthTexture](set-depth-texture.md) | [androidJvm]<br>open fun [setDepthTexture](set-depth-texture.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), depthTexture: Texture)<br>    Sets a DepthTexture to a parameter of the type 'sampler2d' on this material. |
| [setExternalTexture](set-external-texture.md) | [androidJvm]<br>open fun [setExternalTexture](set-external-texture.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), externalTexture: [ExternalTexture](../-external-texture/index.md))<br>Sets an [ExternalTexture](../-external-texture/index.md) to a parameter of type 'samplerExternal' on this material. |
| [setFloat](set-float.md) | [androidJvm]<br>open fun [setFloat](set-float.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setFloat2](set-float2.md) | [androidJvm]<br>open fun [setFloat2](set-float2.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setFloat3](set-float3.md) | [androidJvm]<br>open fun [setFloat3](set-float3.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), value: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md))<br>open fun [setFloat3](set-float3.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), color: [Color](../-color/index.md))<br>open fun [setFloat3](set-float3.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setFloat4](set-float4.md) | [androidJvm]<br>open fun [setFloat4](set-float4.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), color: [Color](../-color/index.md))<br>open fun [setFloat4](set-float4.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), z: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), w: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setInt](set-int.md) | [androidJvm]<br>open fun [setInt](set-int.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setInt2](set-int2.md) | [androidJvm]<br>open fun [setInt2](set-int2.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setInt3](set-int3.md) | [androidJvm]<br>open fun [setInt3](set-int3.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), z: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setInt4](set-int4.md) | [androidJvm]<br>open fun [setInt4](set-int4.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), z: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), w: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setTexture](set-texture.md) | [androidJvm]<br>open fun [setTexture](set-texture.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), texture: [Texture](../-texture/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [internalMaterialInstance](internal-material-instance.md) | [androidJvm]<br>val [internalMaterialInstance](internal-material-instance.md): [Material.IMaterialInstance](../../../../arsceneview/com.google.ar.sceneform.rendering/-material/-i-material-instance/index.md) |
