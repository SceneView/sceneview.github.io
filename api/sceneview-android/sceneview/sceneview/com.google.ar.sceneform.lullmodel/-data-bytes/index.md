//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[DataBytes](index.md)

# DataBytes

[androidJvm]\
class [DataBytes](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataBytes](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null `ByteBuffer` and a zero position. |
| [addValue](add-value.md) | [androidJvm]<br>open fun [addValue](add-value.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [createDataBytes](create-data-bytes.md) | [androidJvm]<br>open fun [createDataBytes](create-data-bytes.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [createValueVector](create-value-vector.md) | [androidJvm]<br>open fun [createValueVector](create-value-vector.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>open fun [createValueVector](create-value-vector.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), data: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [endDataBytes](end-data-bytes.md) | [androidJvm]<br>open fun [endDataBytes](end-data-bytes.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsDataBytes](get-root-as-data-bytes.md) | [androidJvm]<br>open fun [getRootAsDataBytes](get-root-as-data-bytes.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataBytes](index.md)<br>open fun [getRootAsDataBytes](get-root-as-data-bytes.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [DataBytes](index.md)): [DataBytes](index.md) |
| [startDataBytes](start-data-bytes.md) | [androidJvm]<br>open fun [startDataBytes](start-data-bytes.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
| [startValueVector](start-value-vector.md) | [androidJvm]<br>open fun [startValueVector](start-value-vector.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), numElems: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [value](value.md) | [androidJvm]<br>open fun [value](value.md)(j: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [valueAsByteBuffer](value-as-byte-buffer.md) | [androidJvm]<br>open fun [valueAsByteBuffer](value-as-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [valueInByteBuffer](value-in-byte-buffer.md) | [androidJvm]<br>open fun [valueInByteBuffer](value-in-byte-buffer.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [valueLength](value-length.md) | [androidJvm]<br>open fun [valueLength](value-length.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Properties

| Name | Summary |
|---|---|
| [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md) | [androidJvm]<br>val [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md): [ThreadLocal](https://developer.android.com/reference/kotlin/java/lang/ThreadLocal.html)&lt;[Charset](https://developer.android.com/reference/kotlin/java/nio/charset/Charset.html)&gt; |
