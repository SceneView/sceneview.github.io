//[arsceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[RotationController](index.md)

# RotationController

[androidJvm]\
open class [RotationController](index.md) : [BaseTransformationController](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformation-controller/index.md)&lt;[TwistGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-twist-gesture/index.md)&gt; 

Manipulates the rotation of a [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) using a .

## Constructors

| | |
|---|---|
| [RotationController](-rotation-controller.md) | [androidJvm]<br>open fun [RotationController](-rotation-controller.md)(transformableNode: [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md), gestureRecognizer: [TwistGestureRecognizer](../../../../arsceneview/com.google.ar.sceneform.ux/-twist-gesture-recognizer/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [canStartTransformation](can-start-transformation.md) | [androidJvm]<br>open fun [canStartTransformation](can-start-transformation.md)(gesture: [TwistGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-twist-gesture/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getActiveGesture](../-translation-controller/index.md#787825584%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getActiveGesture](../-translation-controller/index.md#787825584%2FFunctions%2F-58641720)(): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof) |
| [getTransformableNode](../-translation-controller/index.md#2034840011%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getTransformableNode](../-translation-controller/index.md#2034840011%2FFunctions%2F-58641720)(): [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) |
| [isEnabled](../-translation-controller/index.md#870050278%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isEnabled](../-translation-controller/index.md#870050278%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTransforming](../-scale-controller/index.md#-1462327427%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isTransforming](../-scale-controller/index.md#-1462327427%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onActivated](../-translation-controller/index.md#1358417673%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onActivated](../-translation-controller/index.md#1358417673%2FFunctions%2F-58641720)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onContinueTransformation](on-continue-transformation.md) | [androidJvm]<br>open fun [onContinueTransformation](on-continue-transformation.md)(gesture: [TwistGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-twist-gesture/index.md)) |
| [onDeactivated](../-translation-controller/index.md#-847875544%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onDeactivated](../-translation-controller/index.md#-847875544%2FFunctions%2F-58641720)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onEndTransformation](on-end-transformation.md) | [androidJvm]<br>open fun [onEndTransformation](on-end-transformation.md)(gesture: [TwistGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-twist-gesture/index.md)) |
| [onFinished](../-translation-controller/index.md#-168863678%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFinished](../-translation-controller/index.md#-168863678%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onFrameUpdated](index.md#-1990201622%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrameUpdated](index.md#-1990201622%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onGestureStarted](../-translation-controller/index.md#1891620872%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onGestureStarted](../-translation-controller/index.md#1891620872%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onUpdated](../-translation-controller/index.md#-550904595%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onUpdated](../-translation-controller/index.md#-550904595%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [setEnabled](../-translation-controller/index.md#1442660156%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setEnabled](../-translation-controller/index.md#1442660156%2FFunctions%2F-58641720)(enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [rotationRateDegrees](rotation-rate-degrees.md) | [androidJvm]<br>private open var [rotationRateDegrees](rotation-rate-degrees.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
