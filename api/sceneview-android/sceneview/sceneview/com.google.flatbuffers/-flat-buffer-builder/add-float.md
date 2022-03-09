//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[addFloat](add-float.md)

# addFloat

[androidJvm]\
open fun [addFloat](add-float.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Add a `float` to the buffer, properly aligned, and grows the buffer (if necessary).

## Parameters

androidJvm

| | |
|---|---|
| x | A `float` to put into the buffer. |

[androidJvm]\
open fun [addFloat](add-float.md)(o: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Add a `float` to a table at `o` into its vtable, with value `x` and default `d`.

## Parameters

androidJvm

| | |
|---|---|
| o | The index into the vtable. |
| x | A `float` to put into the buffer, depending on how defaults are handled. If `force_defaults` is `false`, compare `x` against the default value `d`. If `x` contains the default value, it can be skipped. |
| d | A `float` default value to compare against when `force_defaults` is `false`. |
