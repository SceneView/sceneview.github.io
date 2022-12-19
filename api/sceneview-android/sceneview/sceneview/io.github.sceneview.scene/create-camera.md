//[sceneview](../../index.md)/[io.github.sceneview.scene](index.md)/[createCamera](create-camera.md)

# createCamera

[androidJvm]\
fun [SceneView](../io.github.sceneview/-scene-view/index.md).[createCamera](create-camera.md)(entity: [Entity](../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-1571379623) = EntityManager.get().create()): Camera

Creates and adds a Camera component to a given `entity`

#### Return

A newly created Camera

## Parameters

androidJvm

| | |
|---|---|
| entity | `entity` to add the camera component to |

## Throws

| | |
|---|---|
| [kotlin.IllegalStateException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-state-exception/index.html) | can be thrown if the {@link Camera} couldn't be created |
