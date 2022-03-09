//[sceneview](../../../index.md)/[com.google.ar.sceneform.lullmodel](../index.md)/[ArcDef](index.md)

# ArcDef

[androidJvm]\
class [ArcDef](index.md) : [Struct](../../com.google.flatbuffers/-struct/index.md)

## Functions

| Name | Summary |
|---|---|
| [__assign](__assign.md) | [androidJvm]<br>open fun [__assign](__assign.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ArcDef](index.md) |
| [__init](__init.md) | [androidJvm]<br>open fun [__init](__init.md)(_i: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), _bb: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) |
| [__reset](../../com.google.flatbuffers/-struct/__reset.md) | [androidJvm]<br>open fun [__reset](../../com.google.flatbuffers/-struct/__reset.md)()<br>Resets internal state with a null ByteBuffer and a zero position. |
| [angleSize](angle-size.md) | [androidJvm]<br>open fun [angleSize](angle-size.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Size of the arc measured in radians. |
| [createArcDef](create-arc-def.md) | [androidJvm]<br>open fun [createArcDef](create-arc-def.md)(builder: [FlatBufferBuilder](../../com.google.flatbuffers/-flat-buffer-builder/index.md), startAngle: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), angleSize: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), innerRadius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), outerRadius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), numSamples: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [innerRadius](inner-radius.md) | [androidJvm]<br>open fun [innerRadius](inner-radius.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Inner radius of the arc. |
| [numSamples](num-samples.md) | [androidJvm]<br>open fun [numSamples](num-samples.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Number of samples used for drawing the arc. |
| [outerRadius](outer-radius.md) | [androidJvm]<br>open fun [outerRadius](outer-radius.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Outer radius of the arc. |
| [startAngle](start-angle.md) | [androidJvm]<br>open fun [startAngle](start-angle.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>The angle (in radians) in which the start of the arc should be poised at. |
