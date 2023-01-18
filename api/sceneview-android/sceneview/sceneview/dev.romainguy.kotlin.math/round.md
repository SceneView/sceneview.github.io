//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[round](round.md)

# round

[androidJvm]\
fun [round](round.md)(x: [Half](-half/index.md)): [Half](-half/index.md)

Returns the closest integral half-precision float value to the specified half-precision float value. Special values are handled in the following ways:

- 
   If the specified half-precision float is NaN, the result is NaN
- 
   If the specified half-precision float is infinity (negative or positive), the result is infinity (with the same sign)
- 
   If the specified half-precision float is zero (negative or positive), the result is zero (with the same sign)

#### Return

The value of the specified half-precision float rounded to the nearest half-precision float value

## Parameters

androidJvm

| | |
|---|---|
| x | A half-precision float value |
