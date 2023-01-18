//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addShort](add-short.md)

# addShort

[androidJvm]\
open fun [addShort](add-short.md)(x: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html))

Add a `short` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | A `short` to put into the buffer. |

[androidJvm]\
open fun [addShort](add-short.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add a `short` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | A `short` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | A `short` default value to compare against when `force_defaults` is `false`. |
