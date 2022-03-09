//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[RenderableInstance](index.md)/[getRelativeTransformInverse](get-relative-transform-inverse.md)

# getRelativeTransformInverse

[androidJvm]\

@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)

open fun [getRelativeTransformInverse](get-relative-transform-inverse.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)

Returns the inverse transform of this renderable relative to it's node. This will be non-null if the .sfa file includes a scale other than 1 or has recentering turned on.
