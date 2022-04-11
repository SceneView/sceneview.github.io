//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[MoveGestureDetector](../index.md)/[SimpleOnMoveGestureListener](index.md)

# SimpleOnMoveGestureListener

[androidJvm]\
open class [SimpleOnMoveGestureListener](index.md) : [MoveGestureDetector.OnMoveGestureListener](../-on-move-gesture-listener/index.md)

###  A convenience class to extend when you only want to listen for a subset of

move-related events.

This implements all methods in [OnMoveGestureListener](../-on-move-gesture-listener/index.md) but does nothing. [OnMoveGestureListener.onMove](../-on-move-gesture-listener/on-move.md) returns false so that a subclass can retrieve the accumulated moving factor in an overridden [OnMoveGestureListener.onMoveEnd](../-on-move-gesture-listener/on-move-end.md). [OnMoveGestureListener.onMoveBegin](../-on-move-gesture-listener/on-move-begin.md) returns true.

## Constructors

| | |
|---|---|
| [SimpleOnMoveGestureListener](-simple-on-move-gesture-listener.md) | [androidJvm]<br>fun [SimpleOnMoveGestureListener](-simple-on-move-gesture-listener.md)() |

## Functions

| Name | Summary |
|---|---|
| [onMove](on-move.md) | [androidJvm]<br>open override fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>open override fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onMoveEnd](on-move-end.md) | [androidJvm]<br>open override fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../index.md))<br>Reported by existing pointers going up. |
