//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[filterAugmentedImages](filter-augmented-images.md)

# filterAugmentedImages

[androidJvm]\
open fun &lt;[T](filter-augmented-images.md) : Trackable?&gt; [filterAugmentedImages](filter-augmented-images.md)(trackables: [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingState: TrackingState, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingMethod: AugmentedImage.TrackingMethod): [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;AugmentedImage&gt;

Retrieve a filtered stream containing the Augmented Images with the specified TrackingState and TrackingMethod

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingState | the trackable tracking state or null for no states filter |
| trackingMethod | the trackable tracking method or null for no tracking method filter |
