//[arsceneview](../../../index.md)/[com.google.ar.sceneform](../index.md)/[Trackables](index.md)/[filterPlanes](filter-planes.md)

# filterPlanes

[androidJvm]\
open fun &lt;[T](filter-planes.md) : Trackable?&gt; [filterPlanes](filter-planes.md)(trackables: [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;[T](filter-trackables.md)&gt;, @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)trackingStates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;TrackingState&gt;): [Stream](https://developer.android.com/reference/kotlin/java/util/stream/Stream.html)&lt;Plane&gt;

Retrieve a filtered stream containing the Planes with the specified TrackingStates.

## Parameters

androidJvm

| | |
|---|---|
| trackables | the all or updated trackables retrieved from getAllTrackables or getUpdatedTrackables depending on your needs. |
| trackingStates | the trackable tracking states or null for no states filter |
