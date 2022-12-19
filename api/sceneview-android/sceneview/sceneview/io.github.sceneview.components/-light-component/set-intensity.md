//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[LightComponent](index.md)/[setIntensity](set-intensity.md)

# setIntensity

[androidJvm]\
open fun [setIntensity](set-intensity.md)(watts: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), efficiency: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))

Dynamically updates the light's intensity. The intensity can be negative.

Lightbulb type  | Efficiency -----------------+------------ Incandescent |  2.2% Halogen  |  7.0% LED  |  8.7% Fluorescent  | 10.7%

This call is equivalent to:

```kotlin
Builder.intensity(efficiency * 683 * watts);
```

## Parameters

androidJvm

| | |
|---|---|
| watts | Energy consumed by a lightbulb. It is related to the energy produced and ultimately the brightness by the efficiency parameter. This value is often available on the packaging of commercial lightbulbs. |
| efficiency | Efficiency in percent. This depends on the type of lightbulb used. |
