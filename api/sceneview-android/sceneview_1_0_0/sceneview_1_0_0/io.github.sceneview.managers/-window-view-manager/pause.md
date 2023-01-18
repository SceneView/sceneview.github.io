//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.managers](../index.md)/[WindowViewManager](index.md)/[pause](pause.md)

# pause

[androidJvm]\
fun [pause](pause.md)()

The layout must be removed from the [windowManager](../../../../sceneview_1_0_0/io.github.sceneview.managers/-window-view-manager/window-manager.md) before the activity is destroyed, or the window will be leaked. Therefore we add/remove the ownerView in resume/pause.
