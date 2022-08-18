//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[placementMode](placement-mode.md)

# placementMode

[androidJvm]\
var [placementMode](placement-mode.md): [PlacementMode](../-placement-mode/index.md)

###  How/where does the node is positioned in the real world

Depending on your need, you can change it to adjust between a quick ([PlacementMode.INSTANT](../-placement-mode/-i-n-s-t-a-n-t/index.md)), more accurate ([PlacementMode.DEPTH](../-placement-mode/-d-e-p-t-h/index.md)), only on planes/walls ([PlacementMode.PLANE_HORIZONTAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l/index.md), [PlacementMode.PLANE_VERTICAL](../-placement-mode/-p-l-a-n-e_-v-e-r-t-i-c-a-l/index.md), [PlacementMode.PLANE_HORIZONTAL_AND_VERTICAL](../-placement-mode/-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md)) or auto refining accuracy ([PlacementMode.BEST_AVAILABLE](../-placement-mode/-b-e-s-t_-a-v-a-i-l-a-b-l-e/index.md)) placement. The [hitTest](hit-test.md), [pose](../../../../arsceneview/io.github.sceneview.ar.node/-ar-model-node/pose.md) and [anchor](anchor.md) will be influenced by this choice.
