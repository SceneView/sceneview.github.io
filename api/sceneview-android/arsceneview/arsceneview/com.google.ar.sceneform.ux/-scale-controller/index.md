//[arsceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[ScaleController](index.md)

# ScaleController

[androidJvm]\
open class [ScaleController](index.md) : [BaseTransformationController](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformation-controller/index.md)&lt;[PinchGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-pinch-gesture/index.md)&gt; 

Manipulates the Scale of a [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) using a Pinch . Applies a tunable elastic bounce-back when scaling the  beyond the min/max scale.

## Constructors

| | |
|---|---|
| [ScaleController](-scale-controller.md) | [androidJvm]<br>open fun [ScaleController](-scale-controller.md)(transformableNode: [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md), gestureRecognizer: [PinchGestureRecognizer](../../../../arsceneview/com.google.ar.sceneform.ux/-pinch-gesture-recognizer/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [canStartTransformation](can-start-transformation.md) | [androidJvm]<br>open fun [canStartTransformation](can-start-transformation.md)(gesture: [PinchGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-pinch-gesture/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getActiveGesture](../-translation-controller/index.md#787825584%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getActiveGesture](../-translation-controller/index.md#787825584%2FFunctions%2F-58641720)(): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof) |
| [getTransformableNode](../-translation-controller/index.md#2034840011%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getTransformableNode](../-translation-controller/index.md#2034840011%2FFunctions%2F-58641720)(): [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) |
| [isEnabled](../-translation-controller/index.md#870050278%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isEnabled](../-translation-controller/index.md#870050278%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTransforming](index.md#-1462327427%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isTransforming](index.md#-1462327427%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onActivated](on-activated.md) | [androidJvm]<br>open fun [onActivated](on-activated.md)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onContinueTransformation](on-continue-transformation.md) | [androidJvm]<br>open fun [onContinueTransformation](on-continue-transformation.md)(gesture: [PinchGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-pinch-gesture/index.md)) |
| [onDeactivated](../-translation-controller/index.md#-847875544%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onDeactivated](../-translation-controller/index.md#-847875544%2FFunctions%2F-58641720)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onEndTransformation](on-end-transformation.md) | [androidJvm]<br>open fun [onEndTransformation](on-end-transformation.md)(gesture: [PinchGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-pinch-gesture/index.md)) |
| [onFinished](../-translation-controller/index.md#-168863678%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFinished](../-translation-controller/index.md#-168863678%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onFrameUpdated](on-frame-updated.md) | [androidJvm]<br>open fun [onFrameUpdated](on-frame-updated.md)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onGestureStarted](../-translation-controller/index.md#1891620872%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onGestureStarted](../-translation-controller/index.md#1891620872%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onUpdated](../-translation-controller/index.md#-550904595%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onUpdated](../-translation-controller/index.md#-550904595%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [setEnabled](../-translation-controller/index.md#1442660156%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setEnabled](../-translation-controller/index.md#1442660156%2FFunctions%2F-58641720)(enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_ELASTICITY](-d-e-f-a-u-l-t_-e-l-a-s-t-i-c-i-t-y.md) | [androidJvm]<br>val [DEFAULT_ELASTICITY](-d-e-f-a-u-l-t_-e-l-a-s-t-i-c-i-t-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [DEFAULT_MAX_SCALE](-d-e-f-a-u-l-t_-m-a-x_-s-c-a-l-e.md) | [androidJvm]<br>val [DEFAULT_MAX_SCALE](-d-e-f-a-u-l-t_-m-a-x_-s-c-a-l-e.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [DEFAULT_MIN_SCALE](-d-e-f-a-u-l-t_-m-i-n_-s-c-a-l-e.md) | [androidJvm]<br>val [DEFAULT_MIN_SCALE](-d-e-f-a-u-l-t_-m-i-n_-s-c-a-l-e.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [DEFAULT_SENSITIVITY](-d-e-f-a-u-l-t_-s-e-n-s-i-t-i-v-i-t-y.md) | [androidJvm]<br>val [DEFAULT_SENSITIVITY](-d-e-f-a-u-l-t_-s-e-n-s-i-t-i-v-i-t-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [elasticity](elasticity.md) | [androidJvm]<br>private open var [elasticity](elasticity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [maxScale](max-scale.md) | [androidJvm]<br>private open var [maxScale](max-scale.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [minScale](min-scale.md) | [androidJvm]<br>private open var [minScale](min-scale.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [sensitivity](sensitivity.md) | [androidJvm]<br>private open var [sensitivity](sensitivity.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
