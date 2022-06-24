//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[SceneGestureDetector](index.md)

# SceneGestureDetector

[androidJvm]\
open class [SceneGestureDetector](index.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), listener: [SceneGestureDetector.OnSceneGestureListener](-on-scene-gesture-listener/index.md)?, cameraManipulator: Manipulator?)

###  Responds to Android touch events with listeners and/or camera manipulator

Camera supports one-touch orbit, two-touch pan, and pinch-to-zoom.

## Constructors

| | |
|---|---|
| [SceneGestureDetector](-scene-gesture-detector.md) | [androidJvm]<br>fun [SceneGestureDetector](-scene-gesture-detector.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), listener: [SceneGestureDetector.OnSceneGestureListener](-on-scene-gesture-listener/index.md)? = null, cameraManipulator: Manipulator? = Manipulator.Builder()         .targetPosition(Node.DEFAULT_POSITION.x, Node.DEFAULT_POSITION.y, Node.DEFAULT_POSITION.z)         .viewport(sceneView.width, sceneView.height)         .zoomSpeed(0.05f)         .build(Manipulator.Mode.ORBIT)) |

## Types

| Name | Summary |
|---|---|
| [OnSceneGestureListener](-on-scene-gesture-listener/index.md) | [androidJvm]<br>interface [OnSceneGestureListener](-on-scene-gesture-listener/index.md) : [GestureDetector.OnGestureListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnGestureListener.html), [GestureDetector.OnDoubleTapListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnDoubleTapListener.html), [GestureDetector.OnContextClickListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnContextClickListener.html), [MoveGestureDetector.OnMoveGestureListener](../-move-gesture-detector/-on-move-gesture-listener/index.md), [RotateGestureDetector.OnRotateGestureListener](../-rotate-gesture-detector/-on-rotate-gesture-listener/index.md), [ScaleGestureDetector.OnScaleGestureListener](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.OnScaleGestureListener.html) |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |

## Properties

| Name | Summary |
|---|---|
| [camera](camera.md) | [androidJvm]<br>val [camera](camera.md): [Camera](../../com.google.ar.sceneform/-camera/index.md) |
| [cameraManipulator](camera-manipulator.md) | [androidJvm]<br>var [cameraManipulator](camera-manipulator.md): Manipulator? |
| [filamentGestureDetector](filament-gesture-detector.md) | [androidJvm]<br>open var [filamentGestureDetector](filament-gesture-detector.md): [FilamentGestureDetector](../index.md#-1705903723%2FClasslikes%2F-1571379623)? = null |
| [gestureDetector](gesture-detector.md) | [androidJvm]<br>var [gestureDetector](gesture-detector.md): [GestureDetector](https://developer.android.com/reference/kotlin/android/view/GestureDetector.html)? |
| [lastTouchEvent](last-touch-event.md) | [androidJvm]<br>var [lastTouchEvent](last-touch-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [moveGestureDetector](move-gesture-detector.md) | [androidJvm]<br>open var [moveGestureDetector](move-gesture-detector.md): [MoveGestureDetector](../-move-gesture-detector/index.md)? |
| [rotateGestureDetector](rotate-gesture-detector.md) | [androidJvm]<br>open var [rotateGestureDetector](rotate-gesture-detector.md): [RotateGestureDetector](../-rotate-gesture-detector/index.md)? |
| [scaleGestureDetector](scale-gesture-detector.md) | [androidJvm]<br>open var [scaleGestureDetector](scale-gesture-detector.md): [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)? |
| [sceneView](scene-view.md) | [androidJvm]<br>val [sceneView](scene-view.md): [SceneView](../../io.github.sceneview/-scene-view/index.md) |
