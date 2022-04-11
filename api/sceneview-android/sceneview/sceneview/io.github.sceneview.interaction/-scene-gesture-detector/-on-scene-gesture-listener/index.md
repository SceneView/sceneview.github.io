//[sceneview](../../../../index.md)/[io.github.sceneview.interaction](../../index.md)/[SceneGestureDetector](../index.md)/[OnSceneGestureListener](index.md)

# OnSceneGestureListener

[androidJvm]\
interface [OnSceneGestureListener](index.md) : [GestureDetector.OnGestureListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnGestureListener.html), [GestureDetector.OnDoubleTapListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnDoubleTapListener.html), [GestureDetector.OnContextClickListener](https://developer.android.com/reference/kotlin/android/view/GestureDetector.OnContextClickListener.html), [MoveGestureDetector.OnMoveGestureListener](../../-move-gesture-detector/-on-move-gesture-listener/index.md), [RotateGestureDetector.OnRotateGestureListener](../../-rotate-gesture-detector/-on-rotate-gesture-listener/index.md), [ScaleGestureDetector.OnScaleGestureListener](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.OnScaleGestureListener.html)

## Functions

| Name | Summary |
|---|---|
| [onContextClick](on-context-click.md) | [androidJvm]<br>open override fun [onContextClick](on-context-click.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDoubleTap](on-double-tap.md) | [androidJvm]<br>open override fun [onDoubleTap](on-double-tap.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDoubleTapEvent](on-double-tap-event.md) | [androidJvm]<br>open override fun [onDoubleTapEvent](on-double-tap-event.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onDown](on-down.md) | [androidJvm]<br>open override fun [onDown](on-down.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onFling](on-fling.md) | [androidJvm]<br>open override fun [onFling](on-fling.md)(e1: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)?, e2: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)?, velocityX: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), velocityY: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onLongPress](on-long-press.md) | [androidJvm]<br>open override fun [onLongPress](on-long-press.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)?) |
| [onMove](on-move.md) | [androidJvm]<br>open override fun [onMove](on-move.md)(detector: [MoveGestureDetector](../../-move-gesture-detector/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onMoveBegin](on-move-begin.md) | [androidJvm]<br>open override fun [onMoveBegin](on-move-begin.md)(detector: [MoveGestureDetector](../../-move-gesture-detector/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onMoveEnd](on-move-end.md) | [androidJvm]<br>open override fun [onMoveEnd](on-move-end.md)(detector: [MoveGestureDetector](../../-move-gesture-detector/index.md))<br>Reported by existing pointers going up. |
| [onRotate](on-rotate.md) | [androidJvm]<br>open override fun [onRotate](on-rotate.md)(detector: [RotateGestureDetector](../../-rotate-gesture-detector/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by pointer motion. |
| [onRotateBegin](on-rotate-begin.md) | [androidJvm]<br>open override fun [onRotateBegin](on-rotate-begin.md)(detector: [RotateGestureDetector](../../-rotate-gesture-detector/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Reported by new pointers going down. |
| [onRotateEnd](on-rotate-end.md) | [androidJvm]<br>open override fun [onRotateEnd](on-rotate-end.md)(detector: [RotateGestureDetector](../../-rotate-gesture-detector/index.md))<br>Reported by existing pointers going up. |
| [onScale](on-scale.md) | [androidJvm]<br>open override fun [onScale](on-scale.md)(detector: [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onScaleBegin](on-scale-begin.md) | [androidJvm]<br>open override fun [onScaleBegin](on-scale-begin.md)(detector: [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onScaleEnd](on-scale-end.md) | [androidJvm]<br>open override fun [onScaleEnd](on-scale-end.md)(detector: [ScaleGestureDetector](https://developer.android.com/reference/kotlin/android/view/ScaleGestureDetector.html)) |
| [onScroll](on-scroll.md) | [androidJvm]<br>open override fun [onScroll](on-scroll.md)(e1: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)?, e2: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)?, distanceX: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), distanceY: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onShowPress](on-show-press.md) | [androidJvm]<br>open override fun [onShowPress](on-show-press.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [onSingleTapConfirmed](on-single-tap-confirmed.md) | [androidJvm]<br>open override fun [onSingleTapConfirmed](on-single-tap-confirmed.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onSingleTapUp](on-single-tap-up.md) | [androidJvm]<br>open override fun [onSingleTapUp](on-single-tap-up.md)(e: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [DefaultSceneGestureListener](../../../io.github.sceneview/-scene-view/-default-scene-gesture-listener/index.md) |
