//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addLong](add-long.md)

# addLong

[androidJvm]\
open fun [addLong](add-long.md)(x: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

Add a `long` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | A `long` to put into the buffer. |

[androidJvm]\
open fun [addLong](add-long.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), d: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))

Add a `long` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | A `long` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | A `long` default value to compare against when `force_defaults` is `false`. |
