//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[SubmeshAabb](index.md)

# SubmeshAabb

[androidJvm]\
class [SubmeshAabb](index.md) : [Table](../../com.google.flatbuffers/-table/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [SubmeshAabb](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-table/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-table/__reset.md)()<br>Resets the internal state with a null ByteBuffer and a zero position. |
| [addMaxPosition](add-max-position.md) | [androidJvm]<br>open fun [addMaxPosition](add-max-position.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), maxPositionOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMinPosition](add-min-position.md) | [androidJvm]<br>open fun [addMinPosition](add-min-position.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), minPositionOffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [endSubmeshAabb](end-submesh-aabb.md) | [androidJvm]<br>open fun [endSubmeshAabb](end-submesh-aabb.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md) | [androidJvm]<br>open fun [getByteBuffer](../../com.google.flatbuffers/-table/get-byte-buffer.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>Get the underlying ByteBuffer. |
| [getRootAsSubmeshAabb](get-root-as-submesh-aabb.md) | [androidJvm]<br>open fun [getRootAsSubmeshAabb](get-root-as-submesh-aabb.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [SubmeshAabb](index.md)<br>open fun [getRootAsSubmeshAabb](get-root-as-submesh-aabb.md)(_bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html), obj: [SubmeshAabb](index.md)): [SubmeshAabb](index.md) |
| [maxPosition](max-position.md) | [androidJvm]<br>open fun [maxPosition](max-position.md)(): [Vec3](../-vec3/index.md)<br>open fun [maxPosition](max-position.md)(obj: [Vec3](../-vec3/index.md)): [Vec3](../-vec3/index.md) |
| [minPosition](min-position.md) | [androidJvm]<br>open fun [minPosition](min-position.md)(): [Vec3](../-vec3/index.md)<br>open fun [minPosition](min-position.md)(obj: [Vec3](../-vec3/index.md)): [Vec3](../-vec3/index.md) |
| [startSubmeshAabb](start-submesh-aabb.md) | [androidJvm]<br>open fun [startSubmeshAabb](start-submesh-aabb.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md)) |
