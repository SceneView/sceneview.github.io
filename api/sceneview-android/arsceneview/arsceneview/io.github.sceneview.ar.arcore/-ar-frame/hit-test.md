//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArFrame](index.md)/[hitTest](hit-test.md)

# hitTest

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [hitTest](hit-test.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled, approximateDistance: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistance): HitResult?

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [hitTest](hit-test.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled, approximateDistance: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistance): HitResult?

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.arcore.ArFrame](hit-tests.md) |  |
| [firstValid](../first-valid.md) |  |

[androidJvm]\
fun [hitTest](hit-test.md)(position: [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md), plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), instant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): HitResult?
