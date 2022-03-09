//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[TransformationSystem](index.md)

# TransformationSystem

[androidJvm]\
open class [TransformationSystem](index.md)

Coordinates which [BaseTransformableNode](../-base-transformable-node/index.md) is currently selected. Also, detects various gestures used by the transformation controls of [BaseTransformableNode](../-base-transformable-node/index.md). 

[onTouch](on-touch.md) must be called for gestures to be detected. By default, this is done automatically by ArFragment.

## Constructors

| | |
|---|---|
| [TransformationSystem](-transformation-system.md) | [androidJvm]<br>open fun [TransformationSystem](-transformation-system.md)(displayMetrics: [DisplayMetrics](https://developer.android.com/reference/kotlin/android/util/DisplayMetrics.html), selectionVisualizer: [SelectionVisualizer](../-selection-visualizer/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [addGestureRecognizer](add-gesture-recognizer.md) | [androidJvm]<br>open fun [addGestureRecognizer](add-gesture-recognizer.md)(gestureRecognizer: [BaseGestureRecognizer](../-base-gesture-recognizer/index.md)&lt;out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;)<br>Adds a gesture recognizer to this transformation system. |
| [getDragRecognizer](get-drag-recognizer.md) | [androidJvm]<br>open fun [getDragRecognizer](get-drag-recognizer.md)(): [DragGestureRecognizer](../-drag-gesture-recognizer/index.md)<br>Gets the gesture recognizer for determining when the user performs a drag motion on the touch screen. |
| [getPinchRecognizer](get-pinch-recognizer.md) | [androidJvm]<br>open fun [getPinchRecognizer](get-pinch-recognizer.md)(): [PinchGestureRecognizer](../-pinch-gesture-recognizer/index.md)<br>Gets the gesture recognizer for determining when the user performs a two-finger pinch motion on the touch screen. |
| [getTwistRecognizer](get-twist-recognizer.md) | [androidJvm]<br>open fun [getTwistRecognizer](get-twist-recognizer.md)(): [TwistGestureRecognizer](../-twist-gesture-recognizer/index.md)<br>Gets the gesture recognizer for determining when the user performs a two-finger twist motion on the touch screen. |
| [onTouch](on-touch.md) | [androidJvm]<br>open fun [onTouch](on-touch.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Dispatches touch events to the gesture recognizers contained by this transformation system. |
| [selectNode](select-node.md) | [androidJvm]<br>open fun [selectNode](select-node.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)node: [BaseTransformableNode](../-base-transformable-node/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Sets a [BaseTransformableNode](../-base-transformable-node/index.md) as the selected node if there is no currently selected node or if the currently selected node is not actively being transformed. |

## Properties

| Name | Summary |
|---|---|
| [gesturePointersUtility](gesture-pointers-utility.md) | [androidJvm]<br>private val [gesturePointersUtility](gesture-pointers-utility.md): [GesturePointersUtility](../-gesture-pointers-utility/index.md) |
| [selectedNode](selected-node.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [selectedNode](selected-node.md): [BaseTransformableNode](../-base-transformable-node/index.md) |
| [selectionVisualizer](selection-visualizer.md) | [androidJvm]<br>private open var [selectionVisualizer](selection-visualizer.md): [SelectionVisualizer](../-selection-visualizer/index.md) |
