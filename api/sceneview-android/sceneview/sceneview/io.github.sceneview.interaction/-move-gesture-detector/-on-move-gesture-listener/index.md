//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[MoveGestureDetector](../index.md)/[OnMoveGestureListener](index.md)

# OnMoveGestureListener

[androidJvm]\
interface [OnMoveGestureListener](index.md)

###  The listener for receiving notifications when gestures occur

If you want to listen for all the different gestures then implement this interface. If you only want to listen for a subset it might be easier to extend [SimpleOnMoveGestureListener](../-simple-on-move-gesture-listener/index.md).

An application will receive events in the following order:

- 
   One [onMoveBegin](on-move-begin.md)
- 
   Zero or more [onMove](on-move.md)
- 
   One [onMoveEnd](on-move-end.md)

## Functions

| Name | Summary |
|---|---|
| [onMove](on-move.md) | [androidJvm]<br>abstract fun [onMove](on-move.md)(detector: [MoveGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>abstract fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onMoveEnd](on-move-end.md) | [androidJvm]<br>abstract fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../index.md))<br>Reported by existing pointers going up. |

## Inheritors

| Name |
|---|
| [SimpleOnMoveGestureListener](../-simple-on-move-gesture-listener/index.md) |
| [OnSceneGestureListener](../../-scene-gesture-detector/-on-scene-gesture-listener/index.md) |
