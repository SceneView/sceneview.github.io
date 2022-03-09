//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArFrame](index.md)/[hitTests](hit-tests.md)

# hitTests

[androidJvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)

fun [hitTests](hit-tests.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;HitResult&gt;

###  Performs a ray cast to retrieve the hit trackables

Performs a ray cast from the user's device in the direction of the given location in the camera view. Intersections with detected scene geometry are returned, sorted by distance from the device; the nearest intersection is returned first.

When using:

- 
   **Plane and/or Depth:** Significant geometric leeway is given when returning hit results. For example, a plane hit may be generated if the ray came close, but did not actually hit within the plane extents or plane bounds Plane.isPoseInExtents and Plane.isPoseInPolygon can be used to determine these cases). A point (point cloud) hit is generated when a point is roughly within one finger-width of the provided screen coordinates.
- 
   **Instant Placement:** Ray cast can return a result before ARCore establishes full tracking. The pose and apparent scale of attached objects depends on the InstantPlacementPoint tracking method and the provided approximateDistanceMeters. A discussion of the different tracking methods and the effects of apparent object scale are described in InstantPlacementPoint. This function will succeed only if Config.InstantPlacementMode is com.google.ar.core.Config.InstantPlacementMode.LOCAL_Y_UP in the ARCore session configuration, the ARCore session tracking state is TrackingState.TRACKING }, and there are sufficient feature points to track the point in screen space.
- 
   **Session.Feature.FRONT_CAMERA****:** The returned hit result list will always be empty, as the camera is not TrackingState.TRACKING. Hit testing against tracked faces is not currently supported.

Note: In ARCore 1.24.0 or later on supported devices, if depth is enabled by calling com.google.ar.core.Config.setDepthMode with the value Config.DepthMode.AUTOMATIC, the returned list includes com.google.ar.core.DepthPoint values sampled from the latest computed depth image.

#### Return

an ordered list of intersections with scene geometry, nearest hit first In case of instant placement result, if successful a list containing a single HitResult, otherwise an empty list. The HitResult will have a trackable of type InstantPlacementPoint

## Parameters

androidJvm

| | |
|---|---|
| xPx | x view coordinate in pixels *Default: The view width center* |
| yPx | y view coordinate in pixelsls *Default: The view height center* |
| approximateDistanceMeters | the distance at which to create an InstantPlacementPoint. This is only used while the tracking method for the returned point is InstantPlacementPoint.TrackingMethod.SCREENSPACE_WITH_APPROXIMATE_DISTANCE*Default:* [*ArSession.approximateDistanceMeters*](../-ar-session/approximate-distance-meters.md) |
| plane | enable plane results *Default:* [*ArSession.planeFindingEnabled*](../-ar-session/plane-finding-enabled.md) |
| depth | enable depth results *Default:* [*ArSession.depthEnabled*](../-ar-session/depth-enabled.md) |
| instantPlacement | enable instant placement results *Default:* [*ArSession.instantPlacementEnabled*](../-ar-session/instant-placement-enabled.md) |
