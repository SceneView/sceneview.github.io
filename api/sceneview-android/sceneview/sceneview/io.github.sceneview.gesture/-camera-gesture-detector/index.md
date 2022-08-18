//[sceneview](../../../index.md)/[io.github.sceneview.gesture](../index.md)/[CameraGestureDetector](index.md)

# CameraGestureDetector

[androidJvm]\
open class [CameraGestureDetector](index.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), listener: [CameraGestureDetector.OnCameraGestureListener](-on-camera-gesture-listener/index.md))

Responds to Android touch events and manages a camera manipulator. Supports one-touch orbit, two-touch pan, and pinch-to-zoom.

Copied from filament-utils-android/src/main/java/com/google/android/filament/utils/GestureDetector.kt

## Constructors

| | |
|---|---|
| [CameraGestureDetector](-camera-gesture-detector.md) | [androidJvm]<br>fun [CameraGestureDetector](-camera-gesture-detector.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md), listener: [CameraGestureDetector.OnCameraGestureListener](-on-camera-gesture-listener/index.md)) |

## Types

| Name | Summary |
|---|---|
| [OnCameraGestureListener](-on-camera-gesture-listener/index.md) | [androidJvm]<br>interface [OnCameraGestureListener](-on-camera-gesture-listener/index.md) |
| [SimpleOnCameraGestureListener](-simple-on-camera-gesture-listener/index.md) | [androidJvm]<br>class [SimpleOnCameraGestureListener](-simple-on-camera-gesture-listener/index.md) : [CameraGestureDetector.OnCameraGestureListener](-on-camera-gesture-listener/index.md) |

## Functions

| Name | Summary |
|---|---|
| [onTouchEvent](on-touch-event.md) | [androidJvm]<br>fun [onTouchEvent](on-touch-event.md)(event: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |

## Properties

| Name | Summary |
|---|---|
| [isPanEnabled](is-pan-enabled.md) | [androidJvm]<br>var [isPanEnabled](is-pan-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
