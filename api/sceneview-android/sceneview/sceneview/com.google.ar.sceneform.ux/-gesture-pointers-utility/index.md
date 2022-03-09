//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[GesturePointersUtility](index.md)

# GesturePointersUtility

[androidJvm]\
open class [GesturePointersUtility](index.md)

Retains/Releases pointer Ids so that each pointer can only be used in one gesture at a time. Provides helper functions for converting touch coordinates between pixels and inches.

## Constructors

| | |
|---|---|
| [GesturePointersUtility](-gesture-pointers-utility.md) | [androidJvm]<br>open fun [GesturePointersUtility](-gesture-pointers-utility.md)(displayMetrics: [DisplayMetrics](https://developer.android.com/reference/kotlin/android/util/DisplayMetrics.html)) |

## Functions

| Name | Summary |
|---|---|
| [inchesToPixels](inches-to-pixels.md) | [androidJvm]<br>open fun [inchesToPixels](inches-to-pixels.md)(inches: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [isPointerIdRetained](is-pointer-id-retained.md) | [androidJvm]<br>open fun [isPointerIdRetained](is-pointer-id-retained.md)(pointerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [motionEventToPosition](motion-event-to-position.md) | [androidJvm]<br>open fun [motionEventToPosition](motion-event-to-position.md)(me: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), pointerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [pixelsToInches](pixels-to-inches.md) | [androidJvm]<br>open fun [pixelsToInches](pixels-to-inches.md)(pixels: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [releasePointerId](release-pointer-id.md) | [androidJvm]<br>open fun [releasePointerId](release-pointer-id.md)(pointerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [retainPointerId](retain-pointer-id.md) | [androidJvm]<br>open fun [retainPointerId](retain-pointer-id.md)(pointerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
