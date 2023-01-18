//[sceneview](../../index.md)/[dev.romainguy.kotlin.math](index.md)/[floor](floor.md)

# floor

[androidJvm]\
fun [floor](floor.md)(x: [Half](-half/index.md)): [Half](-half/index.md)

Returns the largest half-precision float value toward positive infinity less than or equal to the specified half-precision float value. Special values are handled in the following ways:

- 
   If the specified half-precision float is NaN, the result is NaN
- 
   If the specified half-precision float is infinity (negative or positive), the result is infinity (with the same sign)
- 
   If the specified half-precision float is zero (negative or positive), the result is zero (with the same sign)

#### Return

The largest half-precision float value toward positive infinity less than or equal to the specified half-precision float value

## Parameters

androidJvm

| | |
|---|---|
| x | A half-precision float value |
