//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[followHitPosition](follow-hit-position.md)

# followHitPosition

[androidJvm]\
var [followHitPosition](follow-hit-position.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true

###  Make the node follow the camera/screen matching real world positions

Controls if an unanchored node should be moved together with the camera.

The node [position](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/position.md) is updated with the realtime ARCore [pose](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/pose.md) at the corresponding [hitPosition](hit-position.md) until it is anchored ([isAnchored](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/is-anchored.md)) or until this this value is set to false.

- 
   While there is no AR tracking information available, the node is following the camera moves so it stays at this camera/screen relative position but without adjusting its position and orientation to the real world
- 
   Then ARCore will try to find the real world position of the node at the [hitPosition](hit-position.md) by looking at its [hitTest](hit-test.md) on each [onArFrame](on-ar-frame.md).
- 
   In case of instant placement disabled, the z position (distance from the camera) will be estimated by the AR surface distance at the (x,y).
- 
   The node rotation will be also adjusted in case of [PlacementMode.DEPTH](../-placement-mode/-d-e-p-t-h/index.md) or depending on the detected planes orientations in case of [PlacementMode.PLANE_HORIZONTAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l/index.md), [PlacementMode.PLANE_VERTICAL](../-placement-mode/-p-l-a-n-e_-v-e-r-t-i-c-a-l/index.md), [PlacementMode.PLANE_HORIZONTAL_AND_VERTICAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md)

HitTest might be consuming. Disable it if your don't need to retrieve the position on each frame on reduce the [maxHitTestPerSecond](max-hit-test-per-second.md)

Disable it if you manage the positioning by yourself or other AR methods (Augmented Images, Augmented Faces,...)

- 
- - 
      true An unanchored node is moved as the camera moves (cursor placement)
- 
   false The pose of an unanchored node is not updated. This is used e.g. while moving a node using gestures.

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.node.ArModelNode](hit-position.md) |  |
