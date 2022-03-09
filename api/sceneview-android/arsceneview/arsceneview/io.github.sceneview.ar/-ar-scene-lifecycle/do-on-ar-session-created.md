//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneLifecycle](index.md)/[doOnArSessionCreated](do-on-ar-session-created.md)

# doOnArSessionCreated

[androidJvm]\
fun [doOnArSessionCreated](do-on-ar-session-created.md)(action: (session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Performs the given action when ARCore session is created

If the ARCore session is already created the action will be performed immediately, otherwise the action will be performed after the ARCore session is next created. The action will only be invoked once, and any listeners will then be removed.
