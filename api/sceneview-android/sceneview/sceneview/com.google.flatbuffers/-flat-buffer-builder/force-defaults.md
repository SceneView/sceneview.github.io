//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[forceDefaults](force-defaults.md)

# forceDefaults

[androidJvm]\
open fun [forceDefaults](force-defaults.md)(forceDefaults: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [FlatBufferBuilder](index.md)

In order to save space, fields that are set to their default value don't get serialized into the buffer. Forcing defaults provides a way to manually disable this optimization.

#### Return

Returns `this`.

## Parameters

androidJvm

| | |
|---|---|
| forceDefaults | When set to `true`, always serializes default values. |
