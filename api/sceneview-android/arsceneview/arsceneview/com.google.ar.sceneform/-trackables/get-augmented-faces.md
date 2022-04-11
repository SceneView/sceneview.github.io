//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[getAugmentedFaces](get-augmented-faces.md)

# getAugmentedFaces

[androidJvm]\
open fun &lt;[T](get-augmented-faces.md) : Trackable?&gt; [getAugmentedFaces](get-augmented-faces.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;AugmentedFace&gt;

Retrieve a filtered collection containing Augmented Faces

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |

[androidJvm]\
open fun &lt;[T](get-augmented-faces.md) : Trackable?&gt; [getAugmentedFaces](get-augmented-faces.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingState: TrackingState): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;AugmentedFace&gt;

Retrieve a filtered collection containing the Augmented Faces with the specified TrackingState and TrackingMethod

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingState | the trackable tracking state or null for no states filter |
