//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[startVector](start-vector.md)

# startVector

[androidJvm]\
open fun [startVector](start-vector.md)(elem_size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), num_elems: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Start a new array/vector of objects. Users usually will not call this directly. The `FlatBuffers` compiler will create a start/end method for vector types in generated code. 

 The expected sequence of calls is: 

1. Start the array using this method.
2. Call [addOffset](add-offset.md) `num_elems` number of times to set the offset of each element in the array.
3. Call [endVector](end-vector.md) to retrieve the offset of the array.

 For example, to create an array of strings, do: 

// Need 10 strings
FlatBufferBuilder builder = new FlatBufferBuilder(existingBuffer);
int[] offsets = new int[10];

for (int i = 0; i &lt; 10; i++) {
  offsets[i] = fbb.createString(" " + i);
}

// Have the strings in the buffer, but don't have a vector.
// Add a vector that references the newly created strings:
builder.startVector(4, offsets.length, 4);

// Add each string to the newly created vector
// The strings are added in reverse order since the buffer
// is filled in back to front
for (int i = offsets.length - 1; i &gt;= 0; i--) {
  builder.addOffset(offsets[i]);
}

// Finish off the vector
int offsetOfTheVector = fbb.endVector();

## Parameters

androidJvm

| | |
|---|---|
| elem_size | The size of each element in the array. |
| num_elems | The number of elements in the array. |
| alignment | The alignment of the array. |
