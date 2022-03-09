//[arsceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[TranslationController](index.md)

# TranslationController

[androidJvm]\
open class [TranslationController](index.md) : [BaseTransformationController](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformation-controller/index.md)&lt;[DragGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture/index.md)&gt; 

Manipulates the position of a [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) using a . If not selected, the [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) will become selected when the [DragGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture/index.md) starts.

## Constructors

| | |
|---|---|
| [TranslationController](-translation-controller.md) | [androidJvm]<br>open fun [TranslationController](-translation-controller.md)(transformableNode: [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md), gestureRecognizer: [DragGestureRecognizer](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture-recognizer/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [canStartTransformation](can-start-transformation.md) | [androidJvm]<br>open fun [canStartTransformation](can-start-transformation.md)(gesture: [DragGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getActiveGesture](index.md#787825584%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getActiveGesture](index.md#787825584%2FFunctions%2F-58641720)(): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof) |
| [getTransformableNode](index.md#2034840011%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [getTransformableNode](index.md#2034840011%2FFunctions%2F-58641720)(): [BaseTransformableNode](../../../../arsceneview/com.google.ar.sceneform.ux/-base-transformable-node/index.md) |
| [isEnabled](index.md#870050278%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [isEnabled](index.md#870050278%2FFunctions%2F-58641720)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTransforming](is-transforming.md) | [androidJvm]<br>open fun [isTransforming](is-transforming.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onActivated](index.md#1358417673%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onActivated](index.md#1358417673%2FFunctions%2F-58641720)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onContinueTransformation](on-continue-transformation.md) | [androidJvm]<br>open fun [onContinueTransformation](on-continue-transformation.md)(gesture: [DragGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture/index.md)) |
| [onDeactivated](index.md#-847875544%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onDeactivated](index.md#-847875544%2FFunctions%2F-58641720)(node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onEndTransformation](on-end-transformation.md) | [androidJvm]<br>open fun [onEndTransformation](on-end-transformation.md)(gesture: [DragGesture](../../../../arsceneview/com.google.ar.sceneform.ux/-drag-gesture/index.md)) |
| [onFinished](index.md#-168863678%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFinished](index.md#-168863678%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onFrameUpdated](on-frame-updated.md) | [androidJvm]<br>open fun [onFrameUpdated](on-frame-updated.md)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), node: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)) |
| [onGestureStarted](index.md#1891620872%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onGestureStarted](index.md#1891620872%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [onUpdated](index.md#-550904595%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onUpdated](index.md#-550904595%2FFunctions%2F-58641720)(gesture: [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)) |
| [setEnabled](index.md#1442660156%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [setEnabled](index.md#1442660156%2FFunctions%2F-58641720)(enabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [allowedPlaneTypes](allowed-plane-types.md) | [androidJvm]<br>private open var [allowedPlaneTypes](allowed-plane-types.md): [EnumSet](https://developer.android.com/reference/kotlin/java/util/EnumSet.html)&lt;Plane.Type&gt; |
