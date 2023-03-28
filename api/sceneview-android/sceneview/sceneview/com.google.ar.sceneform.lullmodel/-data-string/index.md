//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[DataString](index.md)

# DataString

[androidJvm]\
class [DataString](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataString](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null `ByteBuffer` and a zero position. |
| [addValue](add-value.md) | [androidJvm]<br>open fun [addValue](add-value.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [createDataString](create-data-string.md) | [androidJvm]<br>open fun [createDataString](create-data-string.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [endDataString](end-data-string.md) | [androidJvm]<br>open fun [endDataString](end-data-string.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsDataString](get-root-as-data-string.md) | [androidJvm]<br>open fun [getRootAsDataString](get-root-as-data-string.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataString](index.md)<br>open fun [getRootAsDataString](get-root-as-data-string.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [DataString](index.md)): [DataString](index.md) |
| [startDataString](start-data-string.md) | [androidJvm]<br>open fun [startDataString](start-data-string.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
| [value](value.md) | [androidJvm]<br>open fun [value](value.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [valueAsByteBuffer](value-as-byte-buffer.md) | [androidJvm]<br>open fun [valueAsByteBuffer](value-as-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [valueInByteBuffer](value-in-byte-buffer.md) | [androidJvm]<br>open fun [valueInByteBuffer](value-in-byte-buffer.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |

## Properties

| Name | Summary |
|---|---|
| [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md) | [androidJvm]<br>val [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md): [ThreadLocal](https://developer.android.com/reference/kotlin/java/lang/ThreadLocal.html)&lt;[Charset](https://developer.android.com/reference/kotlin/java/nio/charset/Charset.html)&gt; |
