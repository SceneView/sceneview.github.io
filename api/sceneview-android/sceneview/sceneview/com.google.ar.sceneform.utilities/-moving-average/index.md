//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[MovingAverage](index.md)

# MovingAverage

[androidJvm]\
open class [MovingAverage](index.md)

Calculates an exponentially weighted moving average for a series of data.

## Constructors

| | |
|---|---|
| [MovingAverage](-moving-average.md) | [androidJvm]<br>open fun [MovingAverage](-moving-average.md)(initialSample: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Construct an object to track the exponentially weighted moving average for a series of data. |
| [MovingAverage](-moving-average.md) | [androidJvm]<br>open fun [MovingAverage](-moving-average.md)(initialSample: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), weight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Construct an object to track the exponentially weighted moving average for a series of data. |

## Functions

| Name | Summary |
|---|---|
| [addSample](add-sample.md) | [androidJvm]<br>open fun [addSample](add-sample.md)(sample: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Add a sample and calculate a new average. |

## Properties

| Name | Summary |
|---|---|
| [average](average.md) | [androidJvm]<br>private open val [average](average.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [DEFAULT_WEIGHT](-d-e-f-a-u-l-t_-w-e-i-g-h-t.md) | [androidJvm]<br>val [DEFAULT_WEIGHT](-d-e-f-a-u-l-t_-w-e-i-g-h-t.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
