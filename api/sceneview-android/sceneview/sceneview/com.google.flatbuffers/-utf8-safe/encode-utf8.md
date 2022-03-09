//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Utf8Safe](index.md)/[encodeUtf8](encode-utf8.md)

# encodeUtf8

[androidJvm]\
open fun [encodeUtf8](encode-utf8.md)(in: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html), out: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))

Encodes the given characters to the target [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) using UTF-8 encoding. 

Selects an optimal algorithm based on the type of [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) (i.e. heap or direct) and the capabilities of the platform.

## Parameters

androidJvm

| | |
|---|---|
| in | the source string to be encoded |
| out | the target buffer to receive the encoded string. |
