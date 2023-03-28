//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[SceneView](-scene-view.md)

# SceneView

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [SceneView](-scene-view.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)? = null, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, sharedEngine: Engine? = null, sharedNodeManager: [NodeManager](../../io.github.sceneview.managers/-node-manager/index.md)? = null, sharedNodesManipulator: [NodesManipulator](../../io.github.sceneview.gesture/-nodes-manipulator/index.md)? = null, uiHelper: UiHelper = UiHelper(UiHelper.ContextErrorPolicy.DONT_CHECK), cameraNode: [CameraNode](../../io.github.sceneview.nodes/-camera-node/index.md)? = null, cameraManipulator: (width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) -&gt; [CameraManipulator](../index.md#-413489367%2FClasslikes%2F-602047187)? = { width, height -&gt;
        Manipulator.Builder()
            .targetPosition(DEFAULT_MODEL_POSITION)
            .viewport(width, height)
            .build(Manipulator.Mode.ORBIT)
    })
