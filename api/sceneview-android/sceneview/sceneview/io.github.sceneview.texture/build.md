//[sceneview](../../index.md)/[io.github.sceneview.texture](index.md)/[build](build.md)

# build

[androidJvm]\
fun Stream.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): Stream

fun Texture.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): Texture

inline fun &lt;[T](build.md) : Texture.Builder&gt; Deferred&lt;[T](build.md)&gt;.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), crossinline onResult: (Texture) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job
