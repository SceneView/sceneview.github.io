//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[KeyVariantPairDef](index.md)

# KeyVariantPairDef

[androidJvm]\
class [KeyVariantPairDef](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [KeyVariantPairDef](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null ByteBuffer and a zero position. |
| [addHashKey](add-hash-key.md) | [androidJvm]<br>open fun [addHashKey](add-hash-key.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), hashKey: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [addKey](add-key.md) | [androidJvm]<br>open fun [addKey](add-key.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), keyOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addValue](add-value.md) | [androidJvm]<br>open fun [addValue](add-value.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addValueType](add-value-type.md) | [androidJvm]<br>open fun [addValueType](add-value-type.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), valueType: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [createKeyVariantPairDef](create-key-variant-pair-def.md) | [androidJvm]<br>open fun [createKeyVariantPairDef](create-key-variant-pair-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), keyOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), hash_key: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), value_type: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), valueOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [endKeyVariantPairDef](end-key-variant-pair-def.md) | [androidJvm]<br>open fun [endKeyVariantPairDef](end-key-variant-pair-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsKeyVariantPairDef](get-root-as-key-variant-pair-def.md) | [androidJvm]<br>open fun [getRootAsKeyVariantPairDef](get-root-as-key-variant-pair-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [KeyVariantPairDef](index.md)<br>open fun [getRootAsKeyVariantPairDef](get-root-as-key-variant-pair-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [KeyVariantPairDef](index.md)): [KeyVariantPairDef](index.md) |
| [hashKey](hash-key.md) | [androidJvm]<br>open fun [hashKey](hash-key.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [key](key.md) | [androidJvm]<br>open fun [key](key.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
| [keyAsByteBuffer](key-as-byte-buffer.md) | [androidJvm]<br>open fun [keyAsByteBuffer](key-as-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [keyInByteBuffer](key-in-byte-buffer.md) | [androidJvm]<br>open fun [keyInByteBuffer](key-in-byte-buffer.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [startKeyVariantPairDef](start-key-variant-pair-def.md) | [androidJvm]<br>open fun [startKeyVariantPairDef](start-key-variant-pair-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
| [value](value.md) | [androidJvm]<br>open fun [value](value.md)(obj: [Table](../../com.google.flatbuffers/-table/index.md)): [Table](../../com.google.flatbuffers/-table/index.md) |
| [valueType](value-type.md) | [androidJvm]<br>open fun [valueType](value-type.md)(): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
