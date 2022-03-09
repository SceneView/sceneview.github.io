//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addByte](add-byte.md)

# addByte

[androidJvm]\
open fun [addByte](add-byte.md)(x: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html))

Add a `byte` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | A `byte` to put into the buffer. |

[androidJvm]\
open fun [addByte](add-byte.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add a `byte` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | A `byte` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | A `byte` default value to compare against when `force_defaults` is `false`. |
