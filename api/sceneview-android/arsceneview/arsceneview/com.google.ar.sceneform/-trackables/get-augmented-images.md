//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[getAugmentedImages](get-augmented-images.md)

# getAugmentedImages

[androidJvm]\
open fun &lt;[T](get-augmented-images.md) : Trackable?&gt; [getAugmentedImages](get-augmented-images.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;AugmentedImage&gt;

Retrieve a filtered collection containing Augmented Images

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |

[androidJvm]\
open fun &lt;[T](get-augmented-images.md) : Trackable?&gt; [getAugmentedImages](get-augmented-images.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingState: TrackingState, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingMethod: AugmentedImage.TrackingMethod): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;AugmentedImage&gt;

Retrieve a filtered collection containing the Augmented Images with the specified TrackingState and TrackingMethod

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingState | the trackable tracking state or null for no states filter |
| trackingMethod | the trackable tracking method or null for no tracking method filter |
