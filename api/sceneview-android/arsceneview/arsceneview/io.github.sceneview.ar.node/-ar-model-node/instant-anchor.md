//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[instantAnchor](instant-anchor.md)

# instantAnchor

[androidJvm]\
var [instantAnchor](instant-anchor.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false

###  Anchor the node as soon as an AR position/rotation is found/available

If true, the node will be anchored in the real world at the first suitable place available. Depending on your need, you can change the [placementMode](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/placement-mode.md) to adjust between a quick ([PlacementMode.INSTANT](../-placement-mode/-i-n-s-t-a-n-t/index.md)), more accurate ([PlacementMode.DEPTH](../-placement-mode/-d-e-p-t-h/index.md)), only on planes/walls ([PlacementMode.PLANE_HORIZONTAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l/index.md), [PlacementMode.PLANE_VERTICAL](../-placement-mode/-p-l-a-n-e_-v-e-r-t-i-c-a-l/index.md), [PlacementMode.PLANE_HORIZONTAL_AND_VERTICAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md)) or auto refining accuracy ([PlacementMode.BEST_AVAILABLE](../-placement-mode/-b-e-s-t_-a-v-a-i-l-a-b-l-e/index.md)) placement.
