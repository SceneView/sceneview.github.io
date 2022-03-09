//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[finishSizePrefixed](finish-size-prefixed.md)

# finishSizePrefixed

[androidJvm]\
open fun [finishSizePrefixed](finish-size-prefixed.md)(root_table: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Finalize a buffer, pointing to the given `root_table`, with the size prefixed.

## Parameters

androidJvm

| | |
|---|---|
| root_table | An offset to be added to the buffer. |

[androidJvm]\
open fun [finishSizePrefixed](finish-size-prefixed.md)(root_table: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), file_identifier: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))

Finalize a buffer, pointing to the given `root_table`, with the size prefixed.

## Parameters

androidJvm

| | |
|---|---|
| root_table | An offset to be added to the buffer. |
| file_identifier | A FlatBuffer file identifier to be added to the buffer before `root_table`. |
