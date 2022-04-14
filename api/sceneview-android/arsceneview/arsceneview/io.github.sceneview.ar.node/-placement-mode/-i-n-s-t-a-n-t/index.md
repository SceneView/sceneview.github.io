//[arsceneview](../../../../index.md)/[io.github.sceneview.ar.node](../../index.md)/[PlacementMode](../index.md)/[INSTANT](index.md)

# INSTANT

[androidJvm]\
[INSTANT](index.md)()

###  Instantly place only nodes at a fixed orientation and an approximate distance

No AR orientation will be provided = fixed +Y pointing upward, against gravity

This mode is currently intended to be used with hit tests against horizontal surfaces. Hit tests may also be performed against surfaces with any orientation, however:

- 
   The resulting Instant Placement point will always have a pose with +Y pointing upward, against gravity.
- 
   No guarantees are made with respect to orientation of +X and +Z. Specifically, a hit test against a vertical surface, such as a wall, will not result in a pose that's in any way aligned to the plane of the wall, other than +Y being up, against gravity.
- 
   The InstantPlacementPoint's tracking method may never become InstantPlacementPoint.TrackingMethod.FULL_TRACKING } or may take a long time to reach this state. The tracking method remains InstantPlacementPoint.TrackingMethod.SCREENSPACE_WITH_APPROXIMATE_DISTANCE until a (tiny) horizontal plane is fitted at the point of the hit test.

## Properties

| Name | Summary |
|---|---|
| [depthEnabled](../depth-enabled.md) | [androidJvm]<br>val [depthEnabled](../depth-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [instantPlacementDistance](../instant-placement-distance.md) | [androidJvm]<br>var [instantPlacementDistance](../instant-placement-distance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 4.0f |
| [instantPlacementEnabled](../instant-placement-enabled.md) | [androidJvm]<br>val [instantPlacementEnabled](../instant-placement-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [instantPlacementFallback](../instant-placement-fallback.md) | [androidJvm]<br>var [instantPlacementFallback](../instant-placement-fallback.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-372974862%2FProperties%2F-58641720) | [androidJvm]<br>val [name](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-372974862%2FProperties%2F-58641720): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-739389684%2FProperties%2F-58641720) | [androidJvm]<br>val [ordinal](../../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-a-l-l/index.md#-739389684%2FProperties%2F-58641720): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [planeEnabled](../plane-enabled.md) | [androidJvm]<br>val [planeEnabled](../plane-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [planeFindingMode](../plane-finding-mode.md) | [androidJvm]<br>val [planeFindingMode](../plane-finding-mode.md): Config.PlaneFindingMode |
