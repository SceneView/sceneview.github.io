//[arsceneview](../../index.md)/[io.github.sceneview.ar](index.md)/[ARScene](-a-r-scene.md)

# ARScene

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [ARScene](-a-r-scene.md)(modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, nodes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)&gt; = listOf(), planeRenderer: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, onCreate: ([ArSceneView](-ar-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onSessionCreate: [ArSceneView](-ar-scene-view/index.md).(session: [ArSession](../io.github.sceneview.ar.arcore/-ar-session/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onTrackingFailureChanged: [ArSceneView](-ar-scene-view/index.md).(trackingFailureReason: TrackingFailureReason?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onFrame: [ArSceneView](-ar-scene-view/index.md).(arFrame: [ArFrame](../io.github.sceneview.ar.arcore/-ar-frame/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null, onTap: [ArSceneView](-ar-scene-view/index.md).(hitResult: HitResult) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null)
