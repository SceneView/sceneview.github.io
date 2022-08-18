//[sceneview](../../../index.md)/[dev.romainguy.kotlin.math](../index.md)/[Half](index.md)/[toHexString](to-hex-string.md)

# toHexString

[androidJvm]\
fun [toHexString](to-hex-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

Returns a hexadecimal string representation of the specified half-precision float value. If the value is a NaN, the result is "NaN", otherwise the result follows this format:

- 
   If the sign is positive, no sign character appears in the result
- 
   If the sign is negative, the first character is '-'
- 
   If the value is inifinity, the string is "Infinity"
- 
   If the value is 0, the string is "0x0.0p0"
- 
   If the value has a normalized representation, the exponent and significand are represented in the string in two fields. The significand starts with "0x1." followed by its lowercase hexadecimal representation. Trailing zeroes are removed unless all digits are 0, then a single zero is used. The significand representation is followed by the exponent, represented by "p", itself followed by a decimal string of the unbiased exponent
- 
   If the value has a subnormal representation, the significand starts with "0x0." followed by its lowercase hexadecimal representation. Trailing zeroes are removed unless all digits are 0, then a single zero is used. The significand representation is followed by the exponent, represented by "p-14"

#### Return

A hexadecimal string representation of the specified value
