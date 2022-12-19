//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[ScaleGestureDetector](index.md)

# ScaleGestureDetector

[androidJvm]\
open class [ScaleGestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [ScaleGestureDetector.OnScaleListener](-on-scale-listener/index.md)) : [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)

Detects scaling transformation gestures using the supplied [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s

The [android.view.ScaleGestureDetector.OnScaleGestureListener](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.OnScaleGestureListener.html) callback will notify users when a particular gesture event has occurred.

This class should only be used with [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)s reported via touch.

To use this class:

- 
   Create an instance of the {@code ScaleGestureDetector} for your [android.view.View](https://developer.android.com/reference/kotlin/android/view/View.html)
- 
   In the [android.view.View.onTouchEvent](../../io.github.sceneview.texture/-view-stream/index.md#255030538%2FFunctions%2F-1571379623) method ensure you call [onTouchEvent](on-touch-event.md). The methods defined in your callback will be executed when the events occur.

## Constructors

| | |
|---|---|
| [ScaleGestureDetector](-scale-gesture-detector.md) | [androidJvm]<br>fun [ScaleGestureDetector](-scale-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), listener: [ScaleGestureDetector.OnScaleListener](-on-scale-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnScaleListener](-on-scale-listener/index.md) | [androidJvm]<br>interface [OnScaleListener](-on-scale-listener/index.md)<br>The listener for receiving notifications when gestures occur |
| [SimpleOnScaleListener](-simple-on-scale-listener/index.md) | [androidJvm]<br>interface [SimpleOnScaleListener](-simple-on-scale-listener/index.md) : [ScaleGestureDetector.OnScaleListener](-on-scale-listener/index.md)<br>A convenience class to extend when you only want to listen for a subset of  scale-related events |

## Functions

| Name | Summary |
|---|---|
| [getCurrentSpan](index.md#-524472783%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getCurrentSpan](index.md#-524472783%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getCurrentSpanX](index.md#1649932913%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getCurrentSpanX](index.md#1649932913%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getCurrentSpanY](index.md#1680952720%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getCurrentSpanY](index.md#1680952720%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getEventTime](index.md#-1112000435%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getEventTime](index.md#-1112000435%2FFunctions%2F-1571379623)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFocusX](index.md#223524198%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getFocusX](index.md#223524198%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getFocusY](index.md#254544005%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getFocusY](index.md#254544005%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getPreviousSpan](index.md#409773413%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getPreviousSpan](index.md#409773413%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getPreviousSpanX](index.md#546793917%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getPreviousSpanX](index.md#546793917%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getPreviousSpanY](index.md#577813724%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getPreviousSpanY](index.md#577813724%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getScaleFactor](index.md#405757979%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getScaleFactor](index.md#405757979%2FFunctions%2F-1571379623)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getTimeDelta](index.md#1848007785%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getTimeDelta](index.md#1848007785%2FFunctions%2F-1571379623)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [isInProgress](index.md#-1835128510%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [isInProgress](index.md#-1835128510%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isQuickScaleEnabled](index.md#1391900546%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [isQuickScaleEnabled](index.md#1391900546%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isStylusScaleEnabled](index.md#166068747%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [isStylusScaleEnabled](index.md#166068747%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>open override fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setQuickScaleEnabled](index.md#1171614625%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setQuickScaleEnabled](index.md#1171614625%2FFunctions%2F-1571379623)(p0: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setStylusScaleEnabled](index.md#501476598%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setStylusScaleEnabled](index.md#501476598%2FFunctions%2F-1571379623)(p0: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [event](event.md) | [androidJvm]<br>lateinit var [event](event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html) |
