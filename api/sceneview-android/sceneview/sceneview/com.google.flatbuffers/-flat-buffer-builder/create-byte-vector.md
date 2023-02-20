//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[createByteVector](create-byte-vector.md)

# createByteVector

[androidJvm]\
open fun [createByteVector](create-byte-vector.md)(arr: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Create a byte array in the buffer.

#### Return

The offset in the buffer where the encoded array starts.

## Parameters

androidJvm

| | |
|---|---|
| arr | A source array with data |

[androidJvm]\
open fun [createByteVector](create-byte-vector.md)(arr: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;, offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Create a byte array in the buffer.

#### Return

The offset in the buffer where the encoded array starts.

## Parameters

androidJvm

| | |
|---|---|
| arr | a source array with data. |
| offset | the offset in the source array to start copying from. |
| length | the number of bytes to copy from the source array. |

[androidJvm]\
open fun [createByteVector](create-byte-vector.md)(byteBuffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Create a byte array in the buffer. The source [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) position is advanced by [remaining](https://developer.android.com/reference/kotlin/java/nio/Buffer.html#remaining--) places after this call.

#### Return

The offset in the buffer where the encoded array starts.

## Parameters

androidJvm

| | |
|---|---|
| byteBuffer | A source [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) with data. |
