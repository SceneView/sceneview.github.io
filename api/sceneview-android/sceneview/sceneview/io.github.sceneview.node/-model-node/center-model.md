//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[ModelNode](index.md)/[centerModel](center-model.md)

# centerModel

[androidJvm]\
fun [centerModel](center-model.md)(origin: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = Position(x = 0.0f, y = 0.0f, z = 0.0f))

###  Sets up a root transform on the current model to make it centered

## Parameters

androidJvm

| | |
|---|---|
| origin | Coordinate inside the model unit cube from where it is centered<br>-     defaults to 0, 0, 0 will center the model on its center -     center horizontal | bottom aligned = 0, -1, 0 -     left | top aligned: -1, 1, 0 |
