//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneView](index.md)/[onTap](on-tap.md)

# onTap

[androidJvm]\
open fun [onTap](on-tap.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), node: [Node](../../io.github.sceneview.node/-node/index.md)?, renderable: [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?)

###  Invoked when the SceneView is tapped

Calls the onTap listener if it is available.

## Parameters

androidJvm

| | |
|---|---|
| node | The node that was tapped or null. |
| renderable | The ID of the Filament renderable that was tapped. |
| motionEvent | The motion event that caused the tap. |

[androidJvm]\
var [onTap](on-tap.md): (motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), node: [Node](../../io.github.sceneview.node/-node/index.md)?, [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when the SceneView is tapped

Only nodes with renderables or their parent nodes can be tapped since Filament picking is used to find a touched node. The ID of the Filament renderable can be used to determine what part of a model is tapped.

- 
   node - The node that was tapped or null.
- 
   renderable - The ID of the Filament renderable that was tapped.
- 
   motionEvent - The motion event that caused the tap.
