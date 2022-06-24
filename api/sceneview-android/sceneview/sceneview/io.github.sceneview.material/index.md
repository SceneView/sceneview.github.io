//[sceneview](../../index.md)/[io.github.sceneview.material](index.md)

# Package io.github.sceneview.material

## Types

| Name | Summary |
|---|---|
| [MaterialLoader](-material-loader/index.md) | [androidJvm]<br>object [MaterialLoader](-material-loader/index.md) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun Material.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): Material |
| [createInstance](create-instance.md) | [androidJvm]<br>fun Material.[createInstance](create-instance.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): MaterialInstance |
| [destroy](destroy.md) | [androidJvm]<br>fun Material.[destroy](destroy.md)()<br>fun MaterialInstance.[destroy](destroy.md)() |
| [setAoIndex](set-ao-index.md) | [androidJvm]<br>fun MaterialInstance.[setAoIndex](set-ao-index.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setAoStrength](set-ao-strength.md) | [androidJvm]<br>fun MaterialInstance.[setAoStrength](set-ao-strength.md)(value: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setBaseColor](set-base-color.md) | [androidJvm]<br>fun MaterialInstance.[setBaseColor](set-base-color.md)(value: [Color](../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)) |
| [setBaseColorIndex](set-base-color-index.md) | [androidJvm]<br>fun MaterialInstance.[setBaseColorIndex](set-base-color-index.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setBaseColorMap](set-base-color-map.md) | [androidJvm]<br>fun MaterialInstance.[setBaseColorMap](set-base-color-map.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setBaseTexture](set-base-texture.md) | [androidJvm]<br>fun MaterialInstance.[setBaseTexture](set-base-texture.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setEmissiveColor](set-emissive-color.md) | [androidJvm]<br>fun MaterialInstance.[setEmissiveColor](set-emissive-color.md)(value: [Color](../io.github.sceneview.utils/index.md#289679020%2FClasslikes%2F-1571379623)) |
| [setEmissiveIndex](set-emissive-index.md) | [androidJvm]<br>fun MaterialInstance.[setEmissiveIndex](set-emissive-index.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setEmissiveMap](set-emissive-map.md) | [androidJvm]<br>fun MaterialInstance.[setEmissiveMap](set-emissive-map.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setExternalTexture](set-external-texture.md) | [androidJvm]<br>fun MaterialInstance.[setExternalTexture](set-external-texture.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), texture: Texture) |
| [setMetallicFactor](set-metallic-factor.md) | [androidJvm]<br>fun MaterialInstance.[setMetallicFactor](set-metallic-factor.md)(value: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setMetallicRoughnessIndex](set-metallic-roughness-index.md) | [androidJvm]<br>fun MaterialInstance.[setMetallicRoughnessIndex](set-metallic-roughness-index.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setMetallicRoughnessMap](set-metallic-roughness-map.md) | [androidJvm]<br>fun MaterialInstance.[setMetallicRoughnessMap](set-metallic-roughness-map.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setNormalIndex](set-normal-index.md) | [androidJvm]<br>fun MaterialInstance.[setNormalIndex](set-normal-index.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setNormalMap](set-normal-map.md) | [androidJvm]<br>fun MaterialInstance.[setNormalMap](set-normal-map.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setNormalScale](set-normal-scale.md) | [androidJvm]<br>fun MaterialInstance.[setNormalScale](set-normal-scale.md)(value: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setOcclusionMap](set-occlusion-map.md) | [androidJvm]<br>fun MaterialInstance.[setOcclusionMap](set-occlusion-map.md)(texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
| [setParameter](set-parameter.md) | [androidJvm]<br>fun MaterialInstance.[setParameter](set-parameter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Float2](../dev.romainguy.kotlin.math/-float2/index.md))<br>fun MaterialInstance.[setParameter](set-parameter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Float3](../dev.romainguy.kotlin.math/-float3/index.md))<br>fun MaterialInstance.[setParameter](set-parameter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Float4](../dev.romainguy.kotlin.math/-float4/index.md))<br>fun MaterialInstance.[setParameter](set-parameter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Mat4](../dev.romainguy.kotlin.math/-mat4/index.md)) |
| [setRoughnessFactor](set-roughness-factor.md) | [androidJvm]<br>fun MaterialInstance.[setRoughnessFactor](set-roughness-factor.md)(value: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setTexture](set-texture.md) | [androidJvm]<br>fun MaterialInstance.[setTexture](set-texture.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), texture: Texture, textureSampler: TextureSampler = TextureSampler2D()) |
