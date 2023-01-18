//[sceneview](../../../../index.md)/[com.google.flatbuffers](../../index.md)/[FlatBufferBuilder](../index.md)/[ByteBufferFactory](index.md)

# ByteBufferFactory

[androidJvm]\
abstract class [ByteBufferFactory](index.md)

An interface that provides a user of the FlatBufferBuilder class the ability to specify the method in which the internal buffer gets allocated. This allows for alternatives to the default behavior, which is to allocate memory for a new byte-array backed `ByteBuffer` array inside the JVM. The FlatBufferBuilder class contains the HeapByteBufferFactory class to preserve the default behavior in the event that the user does not provide their own implementation of this interface.

## Functions

| Name | Summary |
|---|---|
| [newByteBuffer](new-byte-buffer.md) | [androidJvm]<br>abstract fun [newByteBuffer](new-byte-buffer.md)(capacity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Create a `ByteBuffer` with a given capacity. |
| [releaseByteBuffer](release-byte-buffer.md) | [androidJvm]<br>open fun [releaseByteBuffer](release-byte-buffer.md)(bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))<br>Release a ByteBuffer. |

## Inheritors

| Name |
|---|
| [HeapByteBufferFactory](../-heap-byte-buffer-factory/index.md) |
