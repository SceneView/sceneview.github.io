//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[setModelInstance](set-model-instance.md)

# setModelInstance

[androidJvm]\
open fun [setModelInstance](set-model-instance.md)(modelInstance: [ModelInstance](../../io.github.sceneview.model/index.md#1724271641%2FClasslikes%2F-1571379623)?, autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, scaleToUnits: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null)

###  Set the node model

## Parameters

androidJvm

| | |
|---|---|
| autoAnimate | Plays the animations automatically if the model has one |
| scaleToUnits | Scale the model to fit a unit cube. Default `null` to keep model original size |
| centerOrigin | Center the model origin to this unit cube position<br>-     `null` = Keep the original model center point -     `Position(x = 0.0f, y = 0.0f, z = 0.0f)` = Center the model horizontally and vertically -     `Position(x = 0.0f, y = -1.0f, z = 0.0f)` = center horizontal | bottom aligned -     `Position(x = -1.0f, y = 1.0f, z = 0.0f)` = left | top aligned -     ... |
