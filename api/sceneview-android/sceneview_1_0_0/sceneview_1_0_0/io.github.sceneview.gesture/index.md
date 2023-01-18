//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.gesture](index.md)

# Package io.github.sceneview.gesture

## Types

| Name | Summary |
|---|---|
| [GestureDetector](-gesture-detector/index.md) | [androidJvm]<br>open class [GestureDetector](-gesture-detector/index.md)(view: [SceneView](../io.github.sceneview/-scene-view/index.md), cameraManipulator: [CameraManipulator](../io.github.sceneview/index.md#-413489367%2FClasslikes%2F-602047187)?, nodesManipulator: [NodesManipulator](-nodes-manipulator/index.md))<br>Responds to Android touch events with listeners and/or camera manipulator |
| [MoveGestureDetector](-move-gesture-detector/index.md) | [androidJvm]<br>open class [MoveGestureDetector](-move-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveListener](-move-gesture-detector/-on-move-listener/index.md))<br>Detects move transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s |
| [NodesManipulator](-nodes-manipulator/index.md) | [androidJvm]<br>open class [NodesManipulator](-nodes-manipulator/index.md)(val engine: Engine, val selectionNode: ([Size](../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187)) -&gt; [Node](../io.github.sceneview.nodes/-node/index.md)?) |
| [RotateGestureDetector](-rotate-gesture-detector/index.md) | [androidJvm]<br>open class [RotateGestureDetector](-rotate-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [RotateGestureDetector.OnRotateListener](-rotate-gesture-detector/-on-rotate-listener/index.md))<br>Detects rotation transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s |
| [ScaleGestureDetector](-scale-gesture-detector/index.md) | [androidJvm]<br>open class [ScaleGestureDetector](-scale-gesture-detector/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [ScaleGestureDetector.OnScaleListener](-scale-gesture-detector/-on-scale-listener/index.md)) : [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)<br>Detects scaling transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s |
