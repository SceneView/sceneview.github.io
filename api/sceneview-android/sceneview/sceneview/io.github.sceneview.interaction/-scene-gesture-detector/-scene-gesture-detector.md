//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[SceneGestureDetector](index.md)/[SceneGestureDetector](-scene-gesture-detector.md)

# SceneGestureDetector

[androidJvm]\
fun [SceneGestureDetector](-scene-gesture-detector.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), listener: [SceneGestureDetector.OnSceneGestureListener](-on-scene-gesture-listener/index.md)? = null, cameraManipulator: Manipulator? = Manipulator.Builder()
        .targetPosition(Node.DEFAULT_POSITION.x, Node.DEFAULT_POSITION.y, Node.DEFAULT_POSITION.z)
        .viewport(sceneView.width, sceneView.height)
        .zoomSpeed(0.05f)
        .build(Manipulator.Mode.ORBIT))
