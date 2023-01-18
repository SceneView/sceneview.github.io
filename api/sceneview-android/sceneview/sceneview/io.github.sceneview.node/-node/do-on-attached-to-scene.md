//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[doOnAttachedToScene](do-on-attached-to-scene.md)

# doOnAttachedToScene

[androidJvm]\
fun [doOnAttachedToScene](do-on-attached-to-scene.md)(action: (scene: [SceneView](../../io.github.sceneview/-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Performs the given action when the node is attached to the scene.

If the node is already attached the action will be performed immediately. Else this action will be invoked the first time the scene is attached.

- 
   `scene` - the attached scene
