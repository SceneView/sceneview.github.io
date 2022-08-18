//[sceneview](../../index.md)/[io.github.sceneview.gesture](index.md)

# Package io.github.sceneview.gesture

## Types

| Name | Summary |
|---|---|
| [CameraGestureDetector](-camera-gesture-detector/index.md) | [androidJvm]<br>open class [CameraGestureDetector](-camera-gesture-detector/index.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), listener: [CameraGestureDetector.OnCameraGestureListener](-camera-gesture-detector/-on-camera-gesture-listener/index.md))<br>Responds to Android touch events and manages a camera manipulator. Supports one-touch orbit, two-touch pan, and pinch-to-zoom. |
| [GestureDetector](-gesture-detector/index.md) | [androidJvm]<br>open class [GestureDetector](-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), pickNode: ([MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), ([NodeMotionEvent](-node-motion-event/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), listener: [GestureDetector.OnGestureListener](-gesture-detector/-on-gesture-listener/index.md)) : [GestureDetector](https://developer.android.com/reference/kotlin/android/view/GestureDetector.html)<br>Camera supports one-touch orbit, two-touch pan, and pinch-to-zoom. |
| [MoveGestureDetector](-move-gesture-detector/index.md) | [androidJvm]<br>open class [MoveGestureDetector](-move-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-move-gesture-detector/-on-move-listener/index.md)) |
| [NodeMotionEvent](-node-motion-event/index.md) | [androidJvm]<br>data class [NodeMotionEvent](-node-motion-event/index.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), node: [Node](../io.github.sceneview.node/-node/index.md)?, renderable: [Renderable](../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?) |
| [RotateGestureDetector](-rotate-gesture-detector/index.md) | [androidJvm]<br>open class [RotateGestureDetector](-rotate-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateListener](-rotate-gesture-detector/-on-rotate-listener/index.md))<br>The [OnRotateListener](-rotate-gesture-detector/-on-rotate-listener/index.md) callback will notify users when a particular gesture event has occurred. |
| [ScaleGestureDetector](-scale-gesture-detector/index.md) | [androidJvm]<br>open class [ScaleGestureDetector](-scale-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [ScaleGestureDetector.OnScaleListener](-scale-gesture-detector/-on-scale-listener/index.md)) : [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)<br>The [android.view.ScaleGestureDetector.OnScaleGestureListener](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.OnScaleGestureListener.html) callback will notify users when a particular gesture event has occurred. |

## Properties

| Name | Summary |
|---|---|
| [transform](transform.md) | [androidJvm]<br>val Manipulator.[transform](transform.md): [Transform](../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623) |
