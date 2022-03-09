//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[RenderableInstance](index.md)/[getRelativeTransform](get-relative-transform.md)

# getRelativeTransform

[androidJvm]\

@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)

open fun [getRelativeTransform](get-relative-transform.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)

Returns the transform of this renderable relative to it's node. This will be non-null if the .sfa file includes a scale other than 1 or has recentering turned on.
