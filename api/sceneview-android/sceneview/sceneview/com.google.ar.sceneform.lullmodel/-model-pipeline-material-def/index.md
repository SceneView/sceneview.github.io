//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[ModelPipelineMaterialDef](index.md)

# ModelPipelineMaterialDef

[androidJvm]\
class [ModelPipelineMaterialDef](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ModelPipelineMaterialDef](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null `ByteBuffer` and a zero position. |
| [addMaterial](add-material.md) | [androidJvm]<br>open fun [addMaterial](add-material.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), materialOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addNameOverride](add-name-override.md) | [androidJvm]<br>open fun [addNameOverride](add-name-override.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), nameOverrideOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [createModelPipelineMaterialDef](create-model-pipeline-material-def.md) | [androidJvm]<br>open fun [createModelPipelineMaterialDef](create-model-pipeline-material-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), materialOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), name_overrideOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [endModelPipelineMaterialDef](end-model-pipeline-material-def.md) | [androidJvm]<br>open fun [endModelPipelineMaterialDef](end-model-pipeline-material-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsModelPipelineMaterialDef](get-root-as-model-pipeline-material-def.md) | [androidJvm]<br>open fun [getRootAsModelPipelineMaterialDef](get-root-as-model-pipeline-material-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ModelPipelineMaterialDef](index.md)<br>open fun [getRootAsModelPipelineMaterialDef](get-root-as-model-pipeline-material-def.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [ModelPipelineMaterialDef](index.md)): [ModelPipelineMaterialDef](index.md) |
| [material](material.md) | [androidJvm]<br>open fun [material](material.md)(): [MaterialDef](../-material-def/index.md)<br>Description of the desired material.<br>[androidJvm]<br>open fun [material](material.md)(obj: [MaterialDef](../-material-def/index.md)): [MaterialDef](../-material-def/index.md) |
| [nameOverride](name-override.md) | [androidJvm]<br>open fun [nameOverride](name-override.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Optional replacement name to use at runtime. |
| [nameOverrideAsByteBuffer](name-override-as-byte-buffer.md) | [androidJvm]<br>open fun [nameOverrideAsByteBuffer](name-override-as-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [nameOverrideInByteBuffer](name-override-in-byte-buffer.md) | [androidJvm]<br>open fun [nameOverrideInByteBuffer](name-override-in-byte-buffer.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [startModelPipelineMaterialDef](start-model-pipeline-material-def.md) | [androidJvm]<br>open fun [startModelPipelineMaterialDef](start-model-pipeline-material-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md) | [androidJvm]<br>val [UTF8_CHARSET](../../com.google.flatbuffers/-table/-u-t-f8_-c-h-a-r-s-e-t.md): [ThreadLocal](https://developer.android.com/reference/kotlin/java/lang/ThreadLocal.html)&lt;[Charset](https://developer.android.com/reference/kotlin/java/nio/charset/Charset.html)&gt; |
