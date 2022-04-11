//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[getPlanes](get-planes.md)

# getPlanes

[androidJvm]\
open fun &lt;[T](get-planes.md) : Trackable?&gt; [getPlanes](get-planes.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;Plane&gt;

Retrieve a filtered collection containing Planes

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |

[androidJvm]\
open fun &lt;[T](get-planes.md) : Trackable?&gt; [getPlanes](get-planes.md)(trackables: [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;[T](../../../../arsceneview/com.google.ar.sceneform.ux/-augmented-face-node/check-not-null.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingStates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;TrackingState&gt;): [Collection](https://developer.android.com/reference/kotlin/java/util/Collection.html)&lt;Plane&gt;

Retrieve a filtered collection containing the Planes with the specified TrackingStates.

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingStates | the trackable tracking states or null for no states filter |
