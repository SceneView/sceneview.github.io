//[sceneview](../../../../index.md)/[com.google.flatbuffers](../../index.md)/[FlatBufferBuilder](../index.md)/[ByteBufferFactory](index.md)/[releaseByteBuffer](release-byte-buffer.md)

# releaseByteBuffer

[androidJvm]\
open fun [releaseByteBuffer](release-byte-buffer.md)(bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))

Release a ByteBuffer. Current [FlatBufferBuilder](../index.md) released any reference to it, so it is safe to dispose the buffer or return it to a pool. It is not guaranteed that the buffer has been created with [newByteBuffer](new-byte-buffer.md).

## Parameters

androidJvm

| | |
|---|---|
| bb | the buffer to release |
