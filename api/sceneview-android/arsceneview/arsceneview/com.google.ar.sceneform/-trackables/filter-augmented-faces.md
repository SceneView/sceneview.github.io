//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[filterAugmentedFaces](filter-augmented-faces.md)

# filterAugmentedFaces

[androidJvm]\
open fun &lt;[T](filter-augmented-faces.md) : Trackable?&gt; [filterAugmentedFaces](filter-augmented-faces.md)(trackables: [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingState: TrackingState): [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;AugmentedFace&gt;

Retrieve a filtered stream containing the Augmented Faces with the specified TrackingState and TrackingMethod

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingState | the trackable tracking state or null for no states filter |
