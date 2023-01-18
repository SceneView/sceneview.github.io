//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[GestureDetector](index.md)

# GestureDetector

[androidJvm]\
open class [GestureDetector](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), pickNode: ([MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), ([NodeMotionEvent](../-node-motion-event/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), listener: [GestureDetector.OnGestureListener](-on-gesture-listener/index.md)) : [GestureDetector](https://developer.android.com/reference/kotlin/android/view/GestureDetector.html)

###  Responds to Android touch events with listeners and/or camera manipulator

Camera supports one-touch orbit, two-touch pan, and pinch-to-zoom.

## Constructors

| | |
|---|---|
| [GestureDetector](-gesture-detector.md) | [androidJvm]<br>fun [GestureDetector](-gesture-detector.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), pickNode: ([MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), ([NodeMotionEvent](../-node-motion-event/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html), listener: [GestureDetector.OnGestureListener](-on-gesture-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnGestureListener](-on-gesture-listener/index.md) | [androidJvm]<br>interface [OnGestureListener](-on-gesture-listener/index.md) |
| [SimpleOnGestureListener](-simple-on-gesture-listener/index.md) | [androidJvm]<br>class [SimpleOnGestureListener](-simple-on-gesture-listener/index.md) : [GestureDetector.OnGestureListener](-on-gesture-listener/index.md) |

## Functions

| Name | Summary |
|---|---|
| [isLongpressEnabled](index.md#-1803531730%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [isLongpressEnabled](index.md#-1803531730%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onGenericMotionEvent](index.md#566085196%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onGenericMotionEvent](index.md#566085196%2FFunctions%2F-1571379623)(p0: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>open override fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setContextClickListener](index.md#-468992844%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setContextClickListener](index.md#-468992844%2FFunctions%2F-1571379623)(p0: [GestureDetector.OnContextClickListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnContextClickListener.html)) |
| [setIsLongpressEnabled](index.md#1831650727%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setIsLongpressEnabled](index.md#1831650727%2FFunctions%2F-1571379623)(p0: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setOnDoubleTapListener](index.md#815042863%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setOnDoubleTapListener](index.md#815042863%2FFunctions%2F-1571379623)(p0: [GestureDetector.OnDoubleTapListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnDoubleTapListener.html)) |

## Properties

| Name | Summary |
|---|---|
| [lastTouchEvent](last-touch-event.md) | [androidJvm]<br>var [lastTouchEvent](last-touch-event.md): [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)? = null |
| [moveGestureDetector](move-gesture-detector.md) | [androidJvm]<br>val [moveGestureDetector](move-gesture-detector.md): [MoveGestureDetector](../-move-gesture-detector/index.md) |
| [rotateGestureDetector](rotate-gesture-detector.md) | [androidJvm]<br>val [rotateGestureDetector](rotate-gesture-detector.md): [RotateGestureDetector](../-rotate-gesture-detector/index.md) |
| [scaleGestureDetector](scale-gesture-detector.md) | [androidJvm]<br>val [scaleGestureDetector](scale-gesture-detector.md): [ScaleGestureDetector](../-scale-gesture-detector/index.md) |
