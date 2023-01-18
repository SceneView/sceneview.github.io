//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Struct](index.md)/[__reset](__reset.md)

# __reset

[androidJvm]\
open fun [__reset](__reset.md)()

Resets internal state with a null `ByteBuffer` and a zero position. This method exists primarily to allow recycling Struct instances without risking memory leaks due to `ByteBuffer` references. The instance will be unusable until it is assigned again to a `ByteBuffer`.

## Parameters

androidJvm

| | |
|---|---|
| struct | the instance to reset to initial state |
