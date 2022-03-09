//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[BaseTransformationController](index.md)

# BaseTransformationController

[androidJvm]\
abstract class [BaseTransformationController](index.md)&lt;[T](index.md) : [BaseGesture](../-base-gesture/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;?&gt; : [BaseGestureRecognizer.OnGestureStartedListener](../-base-gesture-recognizer/-on-gesture-started-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt; , [BaseGesture.OnGestureEventListener](../-base-gesture/-on-gesture-event-listener/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt; 

Manipulates the transform properties (i.e. scale/rotation/translation) of a  by responding to Gestures via a [BaseGestureRecognizer](../-base-gesture-recognizer/index.md). 

Example's include, changing the TransformableNode's Scale based on a Pinch Gesture.

## Constructors

| | |
|---|---|
| [BaseTransformationController](-base-transformation-controller.md) | [androidJvm]<br>open fun [BaseTransformationController](-base-transformation-controller.md)(transformableNode: [BaseTransformableNode](../-base-transformable-node/index.md), gestureRecognizer: [BaseGestureRecognizer](../-base-gesture-recognizer/index.md)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;) |

## Functions

| Name | Summary |
|---|---|
| [isEnabled](is-enabled.md) | [androidJvm]<br>open fun [isEnabled](is-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTransforming](is-transforming.md) | [androidJvm]<br>open fun [isTransforming](is-transforming.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onActivated](on-activated.md) | [androidJvm]<br>@[CallSuper](https://developer.android.com/reference/kotlin/androidx/annotation/CallSuper.html)<br>open fun [onActivated](on-activated.md)(node: [Node](../../io.github.sceneview.node/-node/index.md)) |
| [onDeactivated](on-deactivated.md) | [androidJvm]<br>@[CallSuper](https://developer.android.com/reference/kotlin/androidx/annotation/CallSuper.html)<br>open fun [onDeactivated](on-deactivated.md)(node: [Node](../../io.github.sceneview.node/-node/index.md)) |
| [onFinished](on-finished.md) | [androidJvm]<br>open fun [onFinished](on-finished.md)(gesture: [T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)) |
| [onFrameUpdated](on-frame-updated.md) | [androidJvm]<br>open fun [onFrameUpdated](on-frame-updated.md)(frameTime: [FrameTime](../../io.github.sceneview.utils/-frame-time/index.md), node: [Node](../../io.github.sceneview.node/-node/index.md)) |
| [onGestureStarted](on-gesture-started.md) | [androidJvm]<br>open fun [onGestureStarted](on-gesture-started.md)(gesture: [T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)) |
| [onUpdated](on-updated.md) | [androidJvm]<br>open fun [onUpdated](on-updated.md)(gesture: [T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)) |

## Properties

| Name | Summary |
|---|---|
| [activeGesture](active-gesture.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [activeGesture](active-gesture.md): [T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md) |
| [enabled](enabled.md) | [androidJvm]<br>private open var [enabled](enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [transformableNode](transformable-node.md) | [androidJvm]<br>private val [transformableNode](transformable-node.md): [BaseTransformableNode](../-base-transformable-node/index.md) |
