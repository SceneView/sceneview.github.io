//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[onTap](on-tap.md)

# onTap

[androidJvm]\
open fun [onTap](on-tap.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), renderable: [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?)

###  Invoked when the node is tapped

Calls the `onTap` listener if it is available and passes the tap to the parent node.

## Parameters

androidJvm

| | |
|---|---|
| renderable | The ID of the Filament renderable that was tapped. |
| motionEvent | The motion event that caused the tap. |

[androidJvm]\
var [onTap](on-tap.md): (motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when the node is tapped

Only nodes with renderables or their parent nodes can be tapped since Filament picking is used to find a touched node. The ID of the Filament renderable can be used to determine what part of a model is tapped.

- 
   `renderable` - The ID of the Filament renderable that was tapped.
- 
   `motionEvent` - The motion event that caused the tap.
