//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[dataBuffer](data-buffer.md)

# dataBuffer

[androidJvm]\
open fun [dataBuffer](data-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)

Get the ByteBuffer representing the FlatBuffer. Only call this after you've called `finish()`. The actual data starts at the ByteBuffer's current position, not necessarily at `0`.

#### Return

The [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) representing the FlatBuffer
