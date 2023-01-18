//[sceneview](../../../../index.md)/[com.google.flatbuffers](../../index.md)/[FlatBufferBuilder](../index.md)/[HeapByteBufferFactory](index.md)

# HeapByteBufferFactory

[androidJvm]\
class [HeapByteBufferFactory](index.md) : [FlatBufferBuilder.ByteBufferFactory](../-byte-buffer-factory/index.md)

An implementation of the ByteBufferFactory interface that is used when one is not provided by the user. Allocate memory for a new byte-array backed `ByteBuffer` array inside the JVM.

## Functions

| Name | Summary |
|---|---|
| [newByteBuffer](new-byte-buffer.md) | [androidJvm]<br>open fun [newByteBuffer](new-byte-buffer.md)(capacity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Create a `ByteBuffer` with a given capacity. |
| [releaseByteBuffer](../-byte-buffer-factory/release-byte-buffer.md) | [androidJvm]<br>open fun [releaseByteBuffer](../-byte-buffer-factory/release-byte-buffer.md)(bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))<br>Release a ByteBuffer. |

## Properties

| Name | Summary |
|---|---|
| [INSTANCE](-i-n-s-t-a-n-c-e.md) | [androidJvm]<br>val [INSTANCE](-i-n-s-t-a-n-c-e.md): [FlatBufferBuilder.HeapByteBufferFactory](index.md) |
