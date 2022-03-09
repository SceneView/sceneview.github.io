//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[createString](create-string.md)

# createString

[androidJvm]\
open fun [createString](create-string.md)(s: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Encode the string `s` in the buffer using UTF-8. If s is already a [CharBuffer](https://developer.android.com/reference/kotlin/java/nio/CharBuffer.html), this method is allocation free.

#### Return

The offset in the buffer where the encoded string starts.

## Parameters

androidJvm

| | |
|---|---|
| s | The string to encode. |

[androidJvm]\
open fun [createString](create-string.md)(s: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Create a string in the buffer from an already encoded UTF-8 string in a ByteBuffer.

#### Return

The offset in the buffer where the encoded string starts.

## Parameters

androidJvm

| | |
|---|---|
| s | An already encoded UTF-8 string as a `ByteBuffer`. |
