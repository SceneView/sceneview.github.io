//[arsceneview](../../../index.md)/[io.github.sceneview.ar.interaction](../index.md)/[ArSceneGestureDetector](index.md)

# ArSceneGestureDetector

[androidJvm]\
class [ArSceneGestureDetector](index.md)(sceneView: [ArSceneView](../../io.github.sceneview.ar/-ar-scene-view/index.md), listener: [SceneGestureDetector.OnSceneGestureListener](../../../../sceneview/sceneview/io.github.sceneview.interaction/-scene-gesture-detector/-on-scene-gesture-listener/index.md)?, nodeManipulator: [ArNodeManipulator](../-ar-node-manipulator/index.md)?) : [SceneGestureDetector](../../../../sceneview/sceneview/io.github.sceneview.interaction/-scene-gesture-detector/index.md)

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](index.md#-1998157542%2FFunctions%2F-58641720) | [androidJvm]<br>fun [onTouchEvent](index.md#-1998157542%2FFunctions%2F-58641720)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [onTouchNode](on-touch-node.md) | [androidJvm]<br>open override fun [onTouchNode](on-touch-node.md)(selectedNode: [Node](../../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [camera](index.md#1196555625%2FProperties%2F-58641720) | [androidJvm]<br>val [camera](index.md#1196555625%2FProperties%2F-58641720): [Camera](../../../../arsceneview/com.google.ar.sceneform/-camera/index.md) |
| [cameraManipulator](index.md#-914368829%2FProperties%2F-58641720) | [androidJvm]<br>var [cameraManipulator](index.md#-914368829%2FProperties%2F-58641720): Manipulator? |
| [filamentGestureDetector](index.md#1479703123%2FProperties%2F-58641720) | [androidJvm]<br>open var [filamentGestureDetector](index.md#1479703123%2FProperties%2F-58641720): [FilamentGestureDetector](../../../../sceneview/io.github.sceneview.interaction/-filament-gesture-detector/index.md)? |
| [gestureDetector](index.md#-1733266339%2FProperties%2F-58641720) | [androidJvm]<br>var [gestureDetector](index.md#-1733266339%2FProperties%2F-58641720): [GestureDetector](https://developer.android.com/reference/kotlin/android/view/GestureDetector.html)? |
| [lastTouchEvent](index.md#-1763894467%2FProperties%2F-58641720) | [androidJvm]<br>var [lastTouchEvent](index.md#-1763894467%2FProperties%2F-58641720): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? |
| [moveGestureDetector](move-gesture-detector.md) | [androidJvm]<br>open override var [moveGestureDetector](move-gesture-detector.md): [MoveGestureDetector](../../../../sceneview/sceneview/io.github.sceneview.interaction/-move-gesture-detector/index.md)? |
| [nodeManipulator](node-manipulator.md) | [androidJvm]<br>val [nodeManipulator](node-manipulator.md): [ArNodeManipulator](../-ar-node-manipulator/index.md)? |
| [rotateGestureDetector](rotate-gesture-detector.md) | [androidJvm]<br>open override var [rotateGestureDetector](rotate-gesture-detector.md): [RotateGestureDetector](../../../../sceneview/sceneview/io.github.sceneview.interaction/-rotate-gesture-detector/index.md)? |
| [scaleGestureDetector](scale-gesture-detector.md) | [androidJvm]<br>open override var [scaleGestureDetector](scale-gesture-detector.md): [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)? |
| [sceneView](index.md#-1295819589%2FProperties%2F-58641720) | [androidJvm]<br>val [sceneView](index.md#-1295819589%2FProperties%2F-58641720): [SceneView](../../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md) |
