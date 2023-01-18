//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[RotateGestureDetector](index.md)/[onTouchEvent](on-touch-event.md)

# onTouchEvent

[androidJvm]\
fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Accepts MotionEvents and dispatches events to a [OnRotateListener](-on-rotate-listener/index.md) when appropriate

Applications should pass a complete and consistent event stream to this method. A complete and consistent event stream involves all MotionEvents from the initial ACTION_DOWN to the final ACTION_UP or ACTION_CANCEL.

#### Return

`true` if the event was processed and the detector wants to receive the rest of the MotionEvents in this event stream.

## Parameters

androidJvm

| | |
|---|---|
| event | The event to process |
