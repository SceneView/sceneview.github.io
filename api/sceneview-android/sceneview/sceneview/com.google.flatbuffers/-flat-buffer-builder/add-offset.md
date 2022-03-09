//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addOffset](add-offset.md)

# addOffset

[androidJvm]\
open fun [addOffset](add-offset.md)(off: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Adds on offset, relative to where it will be written.

## Parameters

androidJvm

| | |
|---|---|
| off | The offset to add. |

[androidJvm]\
open fun [addOffset](add-offset.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add an `offset` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | An `offset` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | An `offset` default value to compare against when `force_defaults` is `false`. |
