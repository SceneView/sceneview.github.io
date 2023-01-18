//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[VariantMapDef](index.md)

# VariantMapDef

[androidJvm]\
class [VariantMapDef](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [VariantMapDef](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null `ByteBuffer` and a zero position. |
| [addValues](add-values.md) | [androidJvm]<br>open fun [addValues](add-values.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valuesOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [createValuesVector](create-values-vector.md) | [androidJvm]<br>open fun [createValuesVector](create-values-vector.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [createVariantMapDef](create-variant-map-def.md) | [androidJvm]<br>open fun [createVariantMapDef](create-variant-map-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valuesOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [endVariantMapDef](end-variant-map-def.md) | [androidJvm]<br>open fun [endVariantMapDef](end-variant-map-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsVariantMapDef](get-root-as-variant-map-def.md) | [androidJvm]<br>open fun [getRootAsVariantMapDef](get-root-as-variant-map-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [VariantMapDef](index.md)<br>open fun [getRootAsVariantMapDef](get-root-as-variant-map-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [VariantMapDef](index.md)): [VariantMapDef](index.md) |
| [startValuesVector](start-values-vector.md) | [androidJvm]<br>open fun [startValuesVector](start-values-vector.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), numElems: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [startVariantMapDef](start-variant-map-def.md) | [androidJvm]<br>open fun [startVariantMapDef](start-variant-map-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
| [values](values.md) | [androidJvm]<br>open fun [values](values.md)(j: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [KeyVariantPairDef](../-key-variant-pair-def/index.md)<br>open fun [values](values.md)(obj: [KeyVariantPairDef](../-key-variant-pair-def/index.md), j: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [KeyVariantPairDef](../-key-variant-pair-def/index.md) |
| [valuesLength](values-length.md) | [androidJvm]<br>open fun [valuesLength](values-length.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Properties

| Name | Summary |
|---|---|
| [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md) | [androidJvm]<br>val [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md): [ThreadLocal](https://developer.android.com/reference/kotlin/java/lang/ThreadLocal.html)&lt;[Charset](https://developer.android.com/reference/kotlin/java/nio/charset/Charset.html)&gt; |
