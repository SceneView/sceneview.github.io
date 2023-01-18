//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[DataQuat](index.md)

# DataQuat

[androidJvm]\
class [DataQuat](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataQuat](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null `ByteBuffer` and a zero position. |
| [addValue](add-value.md) | [androidJvm]<br>open fun [addValue](add-value.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [endDataQuat](end-data-quat.md) | [androidJvm]<br>open fun [endDataQuat](end-data-quat.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsDataQuat](get-root-as-data-quat.md) | [androidJvm]<br>open fun [getRootAsDataQuat](get-root-as-data-quat.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [DataQuat](index.md)<br>open fun [getRootAsDataQuat](get-root-as-data-quat.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [DataQuat](index.md)): [DataQuat](index.md) |
| [startDataQuat](start-data-quat.md) | [androidJvm]<br>open fun [startDataQuat](start-data-quat.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
| [value](value.md) | [androidJvm]<br>open fun [value](value.md)(): [Quat](../-quat/index.md)<br>open fun [value](value.md)(obj: [Quat](../-quat/index.md)): [Quat](../-quat/index.md) |

## Properties

| Name | Summary |
|---|---|
| [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md) | [androidJvm]<br>val [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md): [ThreadLocal](https://developer.android.com/reference/kotlin/java/lang/ThreadLocal.html)&lt;[Charset](https://developer.android.com/reference/kotlin/java/nio/charset/Charset.html)&gt; |
