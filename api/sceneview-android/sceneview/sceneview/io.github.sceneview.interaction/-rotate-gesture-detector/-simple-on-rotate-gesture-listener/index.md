//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[RotateGestureDetector](../index.md)/[SimpleOnRotateGestureListener](index.md)

# SimpleOnRotateGestureListener

[androidJvm]\
open class [SimpleOnRotateGestureListener](index.md) : [RotateGestureDetector.OnRotateGestureListener](../-on-rotate-gesture-listener/index.md)

###  A convenience class to extend when you only want to listen for a subset of

rotation-related events.

This implements all methods in [OnRotateGestureListener](../-on-rotate-gesture-listener/index.md) but does nothing. [OnRotateGestureListener.onRotate](../-on-rotate-gesture-listener/on-rotate.md) returns false so that a subclass can retrieve the accumulated rotation factor in an overridden [OnRotateGestureListener.onRotateEnd](../-on-rotate-gesture-listener/on-rotate-end.md). [OnRotateGestureListener.onRotateBegin](../-on-rotate-gesture-listener/on-rotate-begin.md) returns true.

## Constructors

| | |
|---|---|
| [SimpleOnRotateGestureListener](-simple-on-rotate-gesture-listener.md) | [androidJvm]<br>fun [SimpleOnRotateGestureListener](-simple-on-rotate-gesture-listener.md)() |

## Functions

| Name | Summary |
|---|---|
| [onRotate](on-rotate.md) | [androidJvm]<br>open override fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>open override fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onRotateEnd](on-rotate-end.md) | [androidJvm]<br>open override fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../index.md))<br>Reported by existing pointers going up. |
