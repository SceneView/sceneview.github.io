//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[onArSessionFailed](on-ar-session-failed.md)

# onArSessionFailed

[androidJvm]\
open override fun [onArSessionFailed](on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html))

[androidJvm]\
var [onArSessionFailed](on-ar-session-failed.md): ([Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when an ARCore error occurred

Registers a callback to be invoked when the ARCore Session cannot be initialized because ARCore is not available on the device or the camera permission has been denied.
