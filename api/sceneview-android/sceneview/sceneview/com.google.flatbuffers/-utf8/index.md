//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Utf8](index.md)

# Utf8

[androidJvm]\
abstract class [Utf8](index.md)

## Functions

| Name | Summary |
|---|---|
| [decodeUtf8](decode-utf8.md) | [androidJvm]<br>abstract fun [decodeUtf8](decode-utf8.md)(buffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Decodes the given UTF-8 portion of the [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) into a [String](https://developer.android.com/reference/kotlin/java/lang/String.html). |
| [encodedLength](encoded-length.md) | [androidJvm]<br>abstract fun [encodedLength](encoded-length.md)(sequence: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of bytes in the UTF-8-encoded form of `sequence`. |
| [encodeUtf8](encode-utf8.md) | [androidJvm]<br>abstract fun [encodeUtf8](encode-utf8.md)(in: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html), out: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))<br>Encodes the given characters to the target [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) using UTF-8 encoding. |
| [getDefault](get-default.md) | [androidJvm]<br>open fun [getDefault](get-default.md)(): [Utf8](index.md)<br>Get the default UTF-8 processor. |
| [setDefault](set-default.md) | [androidJvm]<br>open fun [setDefault](set-default.md)(instance: [Utf8](index.md))<br>Set the default instance of the UTF-8 processor. |

## Inheritors

| Name |
|---|
| [Utf8Safe](../-utf8-safe/index.md) |
