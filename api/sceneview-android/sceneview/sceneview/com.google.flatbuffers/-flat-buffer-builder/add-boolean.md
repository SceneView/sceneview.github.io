//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addBoolean](add-boolean.md)

# addBoolean

[androidJvm]\
open fun [addBoolean](add-boolean.md)(x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Add a `boolean` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | A `boolean` to put into the buffer. |

[androidJvm]\
open fun [addBoolean](add-boolean.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), d: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Add a `boolean` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | A `boolean` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | A `boolean` default value to compare against when `force_defaults` is `false`. |
