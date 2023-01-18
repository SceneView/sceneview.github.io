//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[abs](abs.md)

# abs

[androidJvm]\
fun [abs](abs.md)(x: [Half](-half/index.md)): [Half](-half/index.md)

Returns the absolute value of the specified half-precision float. Special values are handled in the following ways:

- 
   If the specified half-precision float is NaN, the result is NaN
- 
   If the specified half-precision float is zero (negative or positive), the result is positive zero (see [POSITIVE_ZERO](-half/-companion/-p-o-s-i-t-i-v-e_-z-e-r-o.md))
- 
   If the specified half-precision float is infinity (negative or positive), the result is positive infinity (see [POSITIVE_INFINITY](-half/-companion/-p-o-s-i-t-i-v-e_-i-n-f-i-n-i-t-y.md))

#### Return

The absolute value of the specified half-precision float

[androidJvm]\
inline fun [abs](abs.md)(q: [Quaternion](-quaternion/index.md)): [Quaternion](-quaternion/index.md)

inline fun [abs](abs.md)(v: [Float2](-float2/index.md)): [Float2](-float2/index.md)

inline fun [abs](abs.md)(v: [Float3](-float3/index.md)): [Float3](-float3/index.md)

inline fun [abs](abs.md)(v: [Float4](-float4/index.md)): [Float4](-float4/index.md)

inline fun [abs](abs.md)(v: [Half3](-half3/index.md)): [Half3](-half3/index.md)

inline fun [abs](abs.md)(v: [Half4](-half4/index.md)): [Half4](-half4/index.md)
