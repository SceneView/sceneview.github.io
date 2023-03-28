//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[PlacementMode](index.md)

# PlacementMode

[androidJvm]\
enum [PlacementMode](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[PlacementMode](index.md)&gt; 

# How an object is placed on the real world

## Parameters

androidJvm

| | |
|---|---|
| instantPlacementDistance | Distance in meters at which to create an InstantPlacementPoint. This is only used while the tracking method for the returned point is InstantPlacementPoint. |
| instantPlacementFallback | Fallback to instantly place nodes at a fixed orientation and an approximate distance when the base placement type is not available yet or at all. |

## Entries

| | |
|---|---|
| [DISABLED](-d-i-s-a-b-l-e-d/index.md) | [androidJvm]<br>[DISABLED](-d-i-s-a-b-l-e-d/index.md) |
| [PLANE_HORIZONTAL](-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l/index.md) | [androidJvm]<br>[PLANE_HORIZONTAL](-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l/index.md) |
| [PLANE_VERTICAL](-p-l-a-n-e_-v-e-r-t-i-c-a-l/index.md) | [androidJvm]<br>[PLANE_VERTICAL](-p-l-a-n-e_-v-e-r-t-i-c-a-l/index.md) |
| [PLANE_HORIZONTAL_AND_VERTICAL](-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md) | [androidJvm]<br>[PLANE_HORIZONTAL_AND_VERTICAL](-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md) |
| [DEPTH](-d-e-p-t-h/index.md) | [androidJvm]<br>[DEPTH](-d-e-p-t-h/index.md)<br>Not all devices support this mode. In case on non depth enabled device the placement mode will automatically fallback to [PLANE_HORIZONTAL_AND_VERTICAL](-p-l-a-n-e_-h-o-r-i-z-o-n-t-a-l_-a-n-d_-v-e-r-t-i-c-a-l/index.md). |
| [INSTANT](-i-n-s-t-a-n-t/index.md) | [androidJvm]<br>[INSTANT](-i-n-s-t-a-n-t/index.md)<br>No AR orientation will be provided = fixed +Y pointing upward, against gravity |
| [BEST_AVAILABLE](-b-e-s-t_-a-v-a-i-l-a-b-l-e/index.md) | [androidJvm]<br>[BEST_AVAILABLE](-b-e-s-t_-a-v-a-i-l-a-b-l-e/index.md)<br>The node will be placed instantly and then adjusted to fit the best accurate, precise, available placement. |

## Properties

| Name | Summary |
|---|---|
| [depthEnabled](depth-enabled.md) | [androidJvm]<br>val [depthEnabled](depth-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [instantPlacementDistance](instant-placement-distance.md) | [androidJvm]<br>var [instantPlacementDistance](instant-placement-distance.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [instantPlacementEnabled](instant-placement-enabled.md) | [androidJvm]<br>val [instantPlacementEnabled](instant-placement-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [instantPlacementFallback](instant-placement-fallback.md) | [androidJvm]<br>var [instantPlacementFallback](instant-placement-fallback.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [name](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-c-e-n-t-e-r/index.md#-372974862%2FProperties%2F-58641720) | [androidJvm]<br>val [name](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-c-e-n-t-e-r/index.md#-372974862%2FProperties%2F-58641720): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-c-e-n-t-e-r/index.md#-739389684%2FProperties%2F-58641720) | [androidJvm]<br>val [ordinal](../../io.github.sceneview.ar.scene/-plane-renderer/-plane-renderer-mode/-r-e-n-d-e-r_-c-e-n-t-e-r/index.md#-739389684%2FProperties%2F-58641720): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [planeEnabled](plane-enabled.md) | [androidJvm]<br>val [planeEnabled](plane-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [planeFindingMode](plane-finding-mode.md) | [androidJvm]<br>val [planeFindingMode](plane-finding-mode.md): Config.PlaneFindingMode |
