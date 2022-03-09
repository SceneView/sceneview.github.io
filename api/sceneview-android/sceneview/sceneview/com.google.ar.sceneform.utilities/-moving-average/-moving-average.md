//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[MovingAverage](index.md)/[MovingAverage](-moving-average.md)

# MovingAverage

[androidJvm]\
open fun [MovingAverage](-moving-average.md)(initialSample: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Construct an object to track the exponentially weighted moving average for a series of data. The weight is set to a default of 0.9, which is good for data with lots of samples when the average should be resistant to spikes (i.e. frame rate). 

The weight is a ratio between 0 and 1 that represents how much of the previous average is kept compared to the new sample. With a weight of 0.9, 90% of the previous average is kept and 10% of the new sample is added to the average.

## Parameters

androidJvm

| | |
|---|---|
| initialSample | the first sample in the average |

[androidJvm]\
open fun [MovingAverage](-moving-average.md)(initialSample: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), weight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

Construct an object to track the exponentially weighted moving average for a series of data. 

The weight is a ratio between 0 and 1 that represents how much of the previous average is kept compared to the new sample. With a weight of 0.9, 90% of the previous average is kept and 10% of the new sample is added to the average.

## Parameters

androidJvm

| | |
|---|---|
| initialSample | the first sample in the average |
| weight | the weight to used when adding samples |
