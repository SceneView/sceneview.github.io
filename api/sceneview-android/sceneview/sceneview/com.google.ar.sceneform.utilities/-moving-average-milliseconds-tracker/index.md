//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[MovingAverageMillisecondsTracker](index.md)

# MovingAverageMillisecondsTracker

[androidJvm]\
open class [MovingAverageMillisecondsTracker](index.md)

Used to track a [MovingAverage](../-moving-average/index.md) that represents the number of milliseconds that elapse within the execution of a block of code.

## Constructors

| | |
|---|---|
| [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md) | [androidJvm]<br>open fun [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md)() |
| [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md) | [androidJvm]<br>open fun [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md)(weight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md) | [androidJvm]<br>open fun [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md)(clock: [MovingAverageMillisecondsTracker.Clock](../../../../sceneview/com.google.ar.sceneform.utilities/-moving-average-milliseconds-tracker/-clock/index.md)) |
| [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md) | [androidJvm]<br>open fun [MovingAverageMillisecondsTracker](-moving-average-milliseconds-tracker.md)(clock: [MovingAverageMillisecondsTracker.Clock](../../../../sceneview/com.google.ar.sceneform.utilities/-moving-average-milliseconds-tracker/-clock/index.md), weight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [beginSample](begin-sample.md) | [androidJvm]<br>open fun [beginSample](begin-sample.md)()<br>Call at the point in execution when the tracker should start measuring elapsed milliseconds. |
| [endSample](end-sample.md) | [androidJvm]<br>open fun [endSample](end-sample.md)()<br>Call at the point in execution when the tracker should stop measuring elapsed milliseconds and post a new sample. |
| [getAverage](get-average.md) | [androidJvm]<br>open fun [getAverage](get-average.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
