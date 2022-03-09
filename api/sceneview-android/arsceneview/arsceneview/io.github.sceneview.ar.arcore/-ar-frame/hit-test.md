//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArFrame](index.md)/[hitTest](hit-test.md)

# hitTest

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [hitTest](hit-test.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): HitResult?

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [hitTest](hit-test.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): HitResult?

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.arcore.ArFrame](hit-tests.md) |  |
| [firstValid](../first-valid.md) |  |
