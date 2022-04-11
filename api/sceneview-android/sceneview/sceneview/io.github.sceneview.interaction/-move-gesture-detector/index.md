//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[MoveGestureDetector](index.md)

# MoveGestureDetector

[androidJvm]\
class [MoveGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [MoveGestureDetector.OnMoveGestureListener](-on-move-gesture-listener/index.md))

## Types

| Name | Summary |
|---|---|
| [OnMoveGestureListener](-on-move-gesture-listener/index.md) | [androidJvm]<br>interface [OnMoveGestureListener](-on-move-gesture-listener/index.md)<br>If you want to listen for all the different gestures then implement this interface. If you only want to listen for a subset it might be easier to extend [SimpleOnMoveGestureListener](-simple-on-move-gesture-listener/index.md). |
| [SimpleOnMoveGestureListener](-simple-on-move-gesture-listener/index.md) | [androidJvm]<br>open class [SimpleOnMoveGestureListener](-simple-on-move-gesture-listener/index.md) : [MoveGestureDetector.OnMoveGestureListener](-on-move-gesture-listener/index.md)<br>move-related events. |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [context](context.md) | [androidJvm]<br>val [context](context.md): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) |
| [currentMotionEvent](current-motion-event.md) | [androidJvm]<br>var [currentMotionEvent](current-motion-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [firstMotionEvent](first-motion-event.md) | [androidJvm]<br>var [firstMotionEvent](first-motion-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [lastDistanceX](last-distance-x.md) | [androidJvm]<br>var [lastDistanceX](last-distance-x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [lastDistanceY](last-distance-y.md) | [androidJvm]<br>var [lastDistanceY](last-distance-y.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null |
| [listener](listener.md) | [androidJvm]<br>var [listener](listener.md): [MoveGestureDetector.OnMoveGestureListener](-on-move-gesture-listener/index.md) |
