//[sceneview_1_0_0](../../index.md)/[io.github.sceneview](index.md)

# Package io.github.sceneview

## Types

| Name | Summary |
|---|---|
| [CameraGestureDetector](index.md#1247636168%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [CameraGestureDetector](index.md#1247636168%2FClasslikes%2F-602047187) = GestureDetector |
| [CameraManipulator](index.md#-413489367%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [CameraManipulator](index.md#-413489367%2FClasslikes%2F-602047187) = Manipulator |
| [Entity](index.md#1934583341%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Entity](index.md#1934583341%2FClasslikes%2F-602047187) = [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [SceneView](-scene-view/index.md) | [androidJvm]<br>open class [SceneView](-scene-view/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)? = null, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, val sharedEngine: Engine? = null, val sharedNodeManager: [NodeManager](../io.github.sceneview.managers/-node-manager/index.md)? = null, sharedNodesManipulator: [NodesManipulator](../io.github.sceneview.gesture/-nodes-manipulator/index.md)? = null, val uiHelper: UiHelper = UiHelper(UiHelper.ContextErrorPolicy.DONT_CHECK), cameraNode: [CameraNode](../io.github.sceneview.nodes/-camera-node/index.md)? = null, cameraManipulator: (width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) -&gt; [CameraManipulator](index.md#-413489367%2FClasslikes%2F-602047187)? = { width, height -&gt;         Manipulator.Builder()             .targetPosition(DEFAULT_MODEL_POSITION)             .viewport(width, height)             .build(Manipulator.Mode.ORBIT)     }) : [SurfaceView](https://developer.android.com/reference/kotlin/android/view/SurfaceView.html)<br>A SurfaceView that manage rendering and interactions with the 3D scene |

## Functions

| Name | Summary |
|---|---|
| [Scene](-scene.md) | [androidJvm]<br>@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)<br>fun [Scene](-scene.md)(modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, nodes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../io.github.sceneview.nodes/-node/index.md)&gt; = listOf(), onCreate: ([SceneView](-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null) |
