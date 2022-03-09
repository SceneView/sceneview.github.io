//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[FrameTime](index.md)

# FrameTime

[androidJvm]\
data class [FrameTime](index.md)(nanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?)

###  Provides time information for the current frame.

## Parameters

androidJvm

| | |
|---|---|
| nanoseconds | The time when this frame started |
| lastNanoseconds | The time when the previous frame started |

## Constructors

| | |
|---|---|
| [FrameTime](-frame-time.md) | [androidJvm]<br>fun [FrameTime](-frame-time.md)(nanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [fps](fps.md) | [androidJvm]<br>fun [fps](fps.md)(lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [interval](interval.md) | [androidJvm]<br>fun [interval](interval.md)(lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?): [Duration](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.time/-duration/index.html) |
| [intervalSeconds](interval-seconds.md) | [androidJvm]<br>fun [intervalSeconds](interval-seconds.md)(lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Properties

| Name | Summary |
|---|---|
| [fps](fps.md) | [androidJvm]<br>val [fps](fps.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [interval](interval.md) | [androidJvm]<br>val [interval](interval.md): [Duration](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.time/-duration/index.html) |
| [intervalSeconds](interval-seconds.md) | [androidJvm]<br>val [intervalSeconds](interval-seconds.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lastNanoseconds](last-nanoseconds.md) | [androidJvm]<br>val [lastNanoseconds](last-nanoseconds.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [nanoseconds](nanoseconds.md) | [androidJvm]<br>val [nanoseconds](nanoseconds.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
