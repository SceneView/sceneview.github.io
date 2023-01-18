//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[Table](index.md)/[__reset](__reset.md)

# __reset

[androidJvm]\
open fun [__reset](__reset.md)()

Resets the internal state with a null `ByteBuffer` and a zero position. This method exists primarily to allow recycling Table instances without risking memory leaks due to `ByteBuffer` references. The instance will be unusable until it is assigned again to a `ByteBuffer`.
