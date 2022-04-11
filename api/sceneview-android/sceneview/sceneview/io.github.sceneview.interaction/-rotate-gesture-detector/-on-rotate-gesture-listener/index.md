//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[RotateGestureDetector](../index.md)/[OnRotateGestureListener](index.md)

# OnRotateGestureListener

[androidJvm]\
interface [OnRotateGestureListener](index.md)

###  The listener for receiving notifications when gestures occur

If you want to listen for all the different gestures then implement this interface. If you only want to listen for a subset it might be easier to extend [SimpleOnRotateGestureListener](../-simple-on-rotate-gesture-listener/index.md).

An application will receive events in the following order:

- 
   One [onRotateBegin](on-rotate-begin.md)
- 
   Zero or more [onRotate](on-rotate.md)
- 
   One [onRotateEnd](on-rotate-end.md)

## Functions

| Name | Summary |
|---|---|
| [onRotate](on-rotate.md) | [androidJvm]<br>abstract fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>abstract fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onRotateEnd](on-rotate-end.md) | [androidJvm]<br>abstract fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../index.md))<br>Reported by existing pointers going up. |

## Inheritors

| Name |
|---|
| [SimpleOnRotateGestureListener](../-simple-on-rotate-gesture-listener/index.md) |
| [OnSceneGestureListener](../../-scene-gesture-detector/-on-scene-gesture-listener/index.md) |
