//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[max](max.md)

# max

[androidJvm]\
fun [max](max.md)(x: [Half](-half/index.md), y: [Half](-half/index.md)): [Half](-half/index.md)

Returns the larger of two half-precision float values (the value closest to positive infinity). Special values are handled in the following ways:

- 
   If either value is NaN, the result is NaN
- 
   [Half.POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md) is greater than [Half.NEGATIVE_ZERO](-half/-companion/-n-e-g-a-t-i-v-e_-z-e-r-o.md)

#### Return

The larger of the two specified half-precision values

## Parameters

androidJvm

| | |
|---|---|
| x | The first half-precision value |
| y | The second half-precision value |

[androidJvm]\
inline fun [max](max.md)(v: [Float2](-float2/index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

inline fun [max](max.md)(a: [Float2](-float2/index.md), b: [Float2](-float2/index.md)): [Float2](-float2/index.md)

inline fun [max](max.md)(v: [Float3](-float3/index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

inline fun [max](max.md)(a: [Float3](-float3/index.md), b: [Float3](-float3/index.md)): [Float3](-float3/index.md)

inline fun [max](max.md)(v: [Float4](-float4/index.md)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

inline fun [max](max.md)(a: [Float4](-float4/index.md), b: [Float4](-float4/index.md)): [Float4](-float4/index.md)

inline fun [max](max.md)(v: [Half2](-half2/index.md)): [Half](-half/index.md)

inline fun [max](max.md)(a: [Half2](-half2/index.md), b: [Half2](-half2/index.md)): [Half2](-half2/index.md)

inline fun [max](max.md)(v: [Half3](-half3/index.md)): [Half](-half/index.md)

inline fun [max](max.md)(a: [Half3](-half3/index.md), b: [Half3](-half3/index.md)): [Half3](-half3/index.md)

inline fun [max](max.md)(v: [Half4](-half4/index.md)): [Half](-half/index.md)

inline fun [max](max.md)(a: [Half4](-half4/index.md), b: [Half4](-half4/index.md)): [Half4](-half4/index.md)
