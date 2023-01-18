//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addInt](add-int.md)

# addInt

[androidJvm]\
open fun [addInt](add-int.md)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add an `int` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | An `int` to put into the buffer. |

[androidJvm]\
open fun [addInt](add-int.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Add an `int` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | An `int` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | An `int` default value to compare against when `force_defaults` is `false`. |
