//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[setModel](set-model.md)

# setModel

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

open fun [setModel](set-model.md)(renderable: [Renderable](../../com.google.ar.sceneform.rendering/-renderable/index.md)?, autoAnimate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, autoScale: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, centerOrigin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)? = null): [RenderableInstance](../../com.google.ar.sceneform.rendering/-renderable-instance/index.md)?

###  Set the node model

## Parameters

androidJvm

| | |
|---|---|
| autoAnimate | Plays the animations automatically if the model has one |
| autoScale | Scale the model to fit a unit cube |
| centerOrigin | Center the model origin to this unit cube position<br>-     null = Keep the original model center point -     (0, -1, 0) = Center the model horizontally and vertically -     (0, -1, 0) = center horizontal | bottom aligned -     (-1, 1, 0) = left | top aligned -     ... |
