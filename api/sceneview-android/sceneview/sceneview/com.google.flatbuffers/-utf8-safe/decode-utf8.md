//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Utf8Safe](index.md)/[decodeUtf8](decode-utf8.md)

# decodeUtf8

[androidJvm]\
open fun [decodeUtf8](decode-utf8.md)(buffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)

Decodes the given UTF-8 portion of the [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) into a [String](https://developer.android.com/reference/kotlin/java/lang/String.html).

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | if the input is not valid UTF-8. |
