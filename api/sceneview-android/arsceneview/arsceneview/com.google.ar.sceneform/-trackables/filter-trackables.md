//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[filterTrackables](filter-trackables.md)

# filterTrackables

[androidJvm]\
open fun &lt;[T](filter-trackables.md) : Trackable?, [U](filter-trackables.md) : Trackable?&gt; [filterTrackables](filter-trackables.md)(trackables: [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;, type: [Class](https://developer.android.com/reference/kotlin/java/lang/Class.html)&lt;[U](filter-trackables.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingStates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;TrackingState&gt;): [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[U](filter-trackables.md)&gt;

Retrieve a filtered collection containing the trackables with the specified type class and the specified trackingStates.

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingStates | the trackable tracking states or null for no states filter |

[androidJvm]\
open fun &lt;[T](filter-trackables.md) : Trackable?&gt; [filterTrackables](filter-trackables.md)(trackables: [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingStates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;TrackingState&gt;): [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;

Retrieve a filtered collection containing the trackables with the specified trackingStates.

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingStates | the trackable tracking states or null for no states filter |
