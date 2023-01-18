//[sceneview](../../../../index.md)/[com.google.flatbuffers](../../index.md)/[FlatBufferBuilder](../index.md)/[ByteBufferFactory](index.md)/[newByteBuffer](new-byte-buffer.md)

# newByteBuffer

[androidJvm]\
abstract fun [newByteBuffer](new-byte-buffer.md)(capacity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)

Create a `ByteBuffer` with a given capacity. The returned ByteBuf must have a ByteOrder.LITTLE_ENDIAN ByteOrder.

#### Return

Returns the new `ByteBuffer` that was allocated.

## Parameters

androidJvm

| | |
|---|---|
| capacity | The size of the `ByteBuffer` to allocate. |
