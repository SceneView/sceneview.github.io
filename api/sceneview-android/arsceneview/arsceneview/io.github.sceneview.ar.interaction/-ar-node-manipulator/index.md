//[arsceneview](../../../index.md)/[io.github.sceneview.ar.interaction](../index.md)/[ArNodeManipulator](index.md)

# ArNodeManipulator

[androidJvm]\
open class [ArNodeManipulator](index.md)(sceneView: [ArSceneView](../../io.github.sceneview.ar/-ar-scene-view/index.md))

## Functions

| Name | Summary |
|---|---|
| [beginRotate](begin-rotate.md) | [androidJvm]<br>open fun [beginRotate](begin-rotate.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [beginScale](begin-scale.md) | [androidJvm]<br>open fun [beginScale](begin-scale.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [beginTranslate](begin-translate.md) | [androidJvm]<br>open fun [beginTranslate](begin-translate.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [continueTranslate](continue-translate.md) | [androidJvm]<br>open fun [continueTranslate](continue-translate.md)(x: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), y: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [endRotate](end-rotate.md) | [androidJvm]<br>open fun [endRotate](end-rotate.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [endScale](end-scale.md) | [androidJvm]<br>open fun [endScale](end-scale.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [endTranslate](end-translate.md) | [androidJvm]<br>open fun [endTranslate](end-translate.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [rotate](rotate.md) | [androidJvm]<br>open fun [rotate](rotate.md)(deltaRadians: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [scale](scale.md) | [androidJvm]<br>open fun [scale](scale.md)(factor: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [maxZoomScale](max-zoom-scale.md) | [androidJvm]<br>var [maxZoomScale](max-zoom-scale.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 10.0f |
| [minZoomScale](min-zoom-scale.md) | [androidJvm]<br>var [minZoomScale](min-zoom-scale.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.1f |
| [selectedNode](selected-node.md) | [androidJvm]<br>var [selectedNode](selected-node.md): [ArNode](../../io.github.sceneview.ar.node/-ar-node/index.md)? = null |
| [selectedNodeVisualizer](selected-node-visualizer.md) | [androidJvm]<br>open val [selectedNodeVisualizer](selected-node-visualizer.md): [SelectedNodeVisualizer](../../../../sceneview/sceneview/io.github.sceneview.interaction/-selected-node-visualizer/index.md) |
