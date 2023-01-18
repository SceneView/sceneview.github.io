//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[init](init.md)

# init

[androidJvm]\
open fun [init](init.md)(existing_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), bb_factory: [FlatBufferBuilder.ByteBufferFactory](-byte-buffer-factory/index.md)): [FlatBufferBuilder](index.md)

Alternative initializer that allows reusing this object on an existing `ByteBuffer`. This method resets the builder's internal state, but keeps objects that have been allocated for temporary storage.

#### Return

Returns `this`.

## Parameters

androidJvm

| | |
|---|---|
| existing_bb | The byte buffer to reuse. |
| bb_factory | The factory to be used for allocating a new internal buffer if the existing buffer needs to grow |
