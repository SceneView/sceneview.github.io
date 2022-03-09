//[sceneview](../../../index.md)/[com.google.flatbuffers](../index.md)/[FlatBufferBuilder](index.md)/[prep](prep.md)

# prep

[androidJvm]\
open fun [prep](prep.md)(size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), additional_bytes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Prepare to write an element of `size` after `additional_bytes` have been written, e.g. if you write a string, you need to align such the int length field is aligned to [SIZEOF_INT](../../../../sceneview/com.google.flatbuffers/-constants/-s-i-z-e-o-f_-i-n-t.md), and the string data follows it directly. If all you need to do is alignment, `additional_bytes` will be 0.

## Parameters

androidJvm

| | |
|---|---|
| size | This is the of the new element to write. |
| additional_bytes | The padding size. |
