//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Utf8Safe](index.md)

# Utf8Safe

[androidJvm]\
class [Utf8Safe](index.md) : [Utf8](../-utf8/index.md)

A set of low-level, high-performance static utility methods related to the UTF-8 character encoding. This class has no dependencies outside of the core JDK libraries. 

There are several variants of UTF-8. The one implemented by this class is the restricted definition of UTF-8 introduced in Unicode 3.1, which mandates the rejection of "overlong" byte sequences as well as rejection of 3-byte surrogate codepoint byte sequences. Note that the UTF-8 decoder included in Oracle's JDK has been modified to also reject "overlong" byte sequences, but (as of 2011) still accepts 3-byte surrogate codepoint byte sequences. 

The byte sequences considered valid by this class are exactly those that can be roundtrip converted to Strings and back to bytes using the UTF-8 charset, without loss: 

Arrays.equals(bytes, new String(bytes, Internal.UTF_8).getBytes(Internal.UTF_8))

See the Unicode Standard, Table 3-6. UTF-8 Bit Distribution, Table 3-7. Well Formed UTF-8 Byte Sequences.

## Functions

| Name | Summary |
|---|---|
| [decodeUtf8](decode-utf8.md) | [androidJvm]<br>open fun [decodeUtf8](decode-utf8.md)(buffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Decodes the given UTF-8 portion of the [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) into a [String](https://developer.android.com/reference/kotlin/java/lang/String.html). |
| [encodedLength](encoded-length.md) | [androidJvm]<br>open fun [encodedLength](encoded-length.md)(in: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of bytes in the UTF-8-encoded form of sequence. |
| [encodeUtf8](encode-utf8.md) | [androidJvm]<br>open fun [encodeUtf8](encode-utf8.md)(in: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html), out: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))<br>Encodes the given characters to the target [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) using UTF-8 encoding. |
| [getDefault](../-utf8/get-default.md) | [androidJvm]<br>open fun [getDefault](../-utf8/get-default.md)(): [Utf8](../-utf8/index.md)<br>Get the default UTF-8 processor. |
| [setDefault](../-utf8/set-default.md) | [androidJvm]<br>open fun [setDefault](../-utf8/set-default.md)(instance: [Utf8](../-utf8/index.md))<br>Set the default instance of the UTF-8 processor. |
