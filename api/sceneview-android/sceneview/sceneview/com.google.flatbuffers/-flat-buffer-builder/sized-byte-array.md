//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[sizedByteArray](sized-byte-array.md)

# sizedByteArray

[androidJvm]\
open fun [sizedByteArray](sized-byte-array.md)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;

A utility function to copy and return the ByteBuffer data from `start` to `start` + `length` as a `byte[]`.

#### Return

A range copy of the [data buffer](data-buffer.md).

## Parameters

androidJvm

| | |
|---|---|
| start | Start copying at this offset. |
| length | How many bytes to copy. |

## Throws

| | |
|---|---|
| [java.lang.IndexOutOfBoundsException](https://developer.android.com/reference/kotlin/java/lang/IndexOutOfBoundsException.html) | If the range of bytes is ouf of bound. |

[androidJvm]\
open fun [sizedByteArray](sized-byte-array.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;

A utility function to copy and return the ByteBuffer data as a `byte[]`.

#### Return

A full copy of the [data buffer](data-buffer.md).
