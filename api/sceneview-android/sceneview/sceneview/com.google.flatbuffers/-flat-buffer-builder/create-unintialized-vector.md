//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[createUnintializedVector](create-unintialized-vector.md)

# createUnintializedVector

[androidJvm]\
open fun [createUnintializedVector](create-unintialized-vector.md)(elem_size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), num_elems: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)

Create a new array/vector and return a ByteBuffer to be filled later. Call [endVector](end-vector.md) after this method to get an offset to the beginning of vector.

#### Return

ByteBuffer with position and limit set to the space allocated for the array.

## Parameters

androidJvm

| | |
|---|---|
| elem_size | the size of each element in bytes. |
| num_elems | number of elements in the vector. |
| alignment | byte alignment. |
