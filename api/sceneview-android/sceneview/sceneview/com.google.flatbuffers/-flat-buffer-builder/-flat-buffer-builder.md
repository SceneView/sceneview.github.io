//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[FlatBufferBuilder](-flat-buffer-builder.md)

# FlatBufferBuilder

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)(initial_size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bb_factory: [FlatBufferBuilder.ByteBufferFactory](-byte-buffer-factory/index.md))

Start with a buffer of size `initial_size`, then grow as required.

## Parameters

androidJvm

| | |
|---|---|
| initial_size | The initial size of the internal buffer to use. |
| bb_factory | The factory to be used for allocating the internal buffer |

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)(initial_size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bb_factory: [FlatBufferBuilder.ByteBufferFactory](-byte-buffer-factory/index.md), existing_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), utf8: [Utf8](../-utf8/index.md))

Start with a buffer of size `initial_size`, then grow as required.

## Parameters

androidJvm

| | |
|---|---|
| initial_size | The initial size of the internal buffer to use. |
| bb_factory | The factory to be used for allocating the internal buffer |
| existing_bb | The byte buffer to reuse. |
| utf8 | The Utf8 codec |

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)(initial_size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Start with a buffer of size `initial_size`, then grow as required.

## Parameters

androidJvm

| | |
|---|---|
| initial_size | The initial size of the internal buffer to use. |

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)()

Start with a buffer of 1KiB, then grow as required.

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)(existing_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), bb_factory: [FlatBufferBuilder.ByteBufferFactory](-byte-buffer-factory/index.md))

Alternative constructor allowing reuse of [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)s. The builder can still grow the buffer as necessary. User classes should make sure to call [dataBuffer](data-buffer.md) to obtain the resulting encoded message.

## Parameters

androidJvm

| | |
|---|---|
| existing_bb | The byte buffer to reuse. |
| bb_factory | The factory to be used for allocating a new internal buffer if the existing buffer needs to grow |

[androidJvm]\
open fun [FlatBufferBuilder](-flat-buffer-builder.md)(existing_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html))

Alternative constructor allowing reuse of [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)s. The builder can still grow the buffer as necessary. User classes should make sure to call [dataBuffer](data-buffer.md) to obtain the resulting encoded message.

## Parameters

androidJvm

| | |
|---|---|
| existing_bb | The byte buffer to reuse. |
