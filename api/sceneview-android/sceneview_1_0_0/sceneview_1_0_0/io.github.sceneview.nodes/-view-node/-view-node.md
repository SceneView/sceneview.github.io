//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.nodes](../index.md)/[ViewNode](index.md)/[ViewNode](-view-node.md)

# ViewNode

[androidJvm]\
fun [ViewNode](-view-node.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), view: [View](https://developer.android.com/reference/kotlin/android/view/View.html), unlit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, invertFrontFaceWinding: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

fun [ViewNode](-view-node.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), viewResourceId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), unlit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, invertFrontFaceWinding: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

[androidJvm]\
fun [ViewNode](-view-node.md)(engine: Engine, nodeManager: [NodeManager](../../io.github.sceneview.managers/-node-manager/index.md), viewWindowViewManager: [WindowViewManager](../../io.github.sceneview.managers/-window-view-manager/index.md), materialLoader: [MaterialLoader](../../io.github.sceneview.loaders/-material-loader/index.md), view: [View](https://developer.android.com/reference/kotlin/android/view/View.html), unlit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, invertFrontFaceWinding: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

## Parameters

androidJvm

| | |
|---|---|
| view | The 2D Android [View](https://developer.android.com/reference/kotlin/android/view/View.html) that is rendered by this [ViewNode](index.md) |
| unlit | True to disable all lights influences on the rendered view |
| invertFrontFaceWinding | Inverts the winding order of front faces. Inverting the winding order of front faces is useful when rendering mirrored reflections (water, mirror surfaces, front camera in AR, etc.). True to invert front faces, false otherwise |
