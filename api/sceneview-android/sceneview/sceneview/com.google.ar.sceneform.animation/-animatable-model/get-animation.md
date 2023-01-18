//[sceneview](../../../index.md)/[com.google.ar.sceneform.animation](../index.md)/[AnimatableModel](index.md)/[getAnimation](get-animation.md)

# getAnimation

[androidJvm]\
abstract fun [getAnimation](get-animation.md)(animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [ModelAnimation](../-model-animation/index.md)

Get the associated [ModelAnimation](../-model-animation/index.md) at the given index or throw an [IndexOutOfBoundsException](https://developer.android.com/reference/kotlin/java/lang/IndexOutOfBoundsException.html).

## Parameters

androidJvm

| | |
|---|---|
| animationIndex | Zero-based index for the animation of interest. |

[androidJvm]\
open fun [getAnimation](get-animation.md)(name: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [ModelAnimation](../-model-animation/index.md)

Get the associated [ModelAnimation](../-model-animation/index.md) by name or null if none exist with the given name.
