//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addStruct](add-struct.md)

# addStruct

[androidJvm]\
open fun [addStruct](add-struct.md)(voffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add a struct to the table. Structs are stored inline, so nothing additional is being added.

## Parameters

androidJvm

| | |
|---|---|
| voffset | The index into the vtable. |
| x | The offset of the created struct. |
| d | The default value is always `0`. |
