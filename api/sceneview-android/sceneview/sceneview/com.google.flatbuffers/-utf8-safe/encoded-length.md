//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Utf8Safe](index.md)/[encodedLength](encoded-length.md)

# encodedLength

[androidJvm]\
open fun [encodedLength](encoded-length.md)(in: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Returns the number of bytes in the UTF-8-encoded form of `sequence`. For a string, this method is equivalent to `string.getBytes(UTF_8).length`, but is more efficient in both time and space.

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | if `sequence` contains ill-formed UTF-16 (unpaired surrogates) |
