//[arsceneview](../../index.md)/[io.github.sceneview.ar.arcore](index.md)

# Package io.github.sceneview.ar.arcore

## Types

| Name | Summary |
|---|---|
| [ArFrame](-ar-frame/index.md) | [androidJvm]<br>data class [ArFrame](-ar-frame/index.md)(val session: [ArSession](-ar-session/index.md), val time: [FrameTime](../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), val frame: Frame) |
| [ArSession](-ar-session/index.md) | [androidJvm]<br>class [ArSession](-ar-session/index.md)(val lifecycle: [ArSceneLifecycle](../io.github.sceneview.ar/-ar-scene-lifecycle/index.md), features: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt; = setOf()) : Session, [ArSceneLifecycleObserver](../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md) |
| [LightEstimationMode](-light-estimation-mode/index.md) | [androidJvm]<br>enum [LightEstimationMode](-light-estimation-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[LightEstimationMode](-light-estimation-mode/index.md)&gt; <br>ARCore estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation |
| [LightEstimator](-light-estimator/index.md) | [androidJvm]<br>class [LightEstimator](-light-estimator/index.md)(lifecycle: [ArSceneLifecycle](../io.github.sceneview.ar/-ar-scene-lifecycle/index.md), onUpdated: ([LightEstimator](-light-estimator/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) : [ArSceneLifecycleObserver](../io.github.sceneview.ar/-ar-scene-lifecycle-observer/index.md)<br>ARCore will estimate lighting to provide directional light, ambient spherical harmonics, and reflection cubemap estimation |

## Functions

| Name | Summary |
|---|---|
| [calculateDistanceToPlane](calculate-distance-to-plane.md) | [androidJvm]<br>fun Pose.[calculateDistanceToPlane](calculate-distance-to-plane.md)(cameraPose: Pose): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [createAnchor](create-anchor.md) | [androidJvm]<br>fun Earth.[createAnchor](create-anchor.md)(latitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), longitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), altitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rotation: [Rotation](../../../sceneview/io.github.sceneview.math/-rotation/index.md)): Anchor<br>fun Earth.[createAnchor](create-anchor.md)(latitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), longitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), altitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), quaternion: Quaternion): Anchor |
| [distanceTo](distance-to.md) | [androidJvm]<br>fun Pose.[distanceTo](distance-to.md)(other: Pose): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>Calculate the normal distance from this to the other, the given other pose should have y axis parallel to plane's normal, for example plane's center pose or hit test pose. |
| [firstValid](first-valid.md) | [androidJvm]<br>fun [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)&lt;HitResult&gt;.[firstValid](first-valid.md)(camera: Camera, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): HitResult?<br>Hits are sorted by depth. Consider only closest hit on a plane, Oriented Point, Depth Point, or Instant Placement Point. |

## Properties

| Name | Summary |
|---|---|
| [cloudAnchorEnabled](cloud-anchor-enabled.md) | [androidJvm]<br>var Config.[cloudAnchorEnabled](cloud-anchor-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [geospatialEnabled](geospatial-enabled.md) | [androidJvm]<br>var Config.[geospatialEnabled](geospatial-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [instantPlacementEnabled](instant-placement-enabled.md) | [androidJvm]<br>var Config.[instantPlacementEnabled](instant-placement-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTracking](is-tracking.md) | [androidJvm]<br>val Camera.[isTracking](is-tracking.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Keep the screen unlocked while tracking, but allow it to lock when tracking stops.<br>val Trackable.[isTracking](is-tracking.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)val HitResult.[isTracking](is-tracking.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)val AugmentedImage.[isTracking](is-tracking.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [planeFindingEnabled](plane-finding-enabled.md) | [androidJvm]<br>var Config.[planeFindingEnabled](plane-finding-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [position](position.md) | [androidJvm]<br>val Pose.[position](position.md): [Position](../../../sceneview/io.github.sceneview.math/-position/index.md) |
| [quaternion](quaternion.md) | [androidJvm]<br>val Pose.[quaternion](quaternion.md): Quaternion |
| [rotation](rotation.md) | [androidJvm]<br>val Pose.[rotation](rotation.md): [Rotation](../../../sceneview/io.github.sceneview.math/-rotation/index.md) |
| [transform](transform.md) | [androidJvm]<br>val Pose.[transform](transform.md): [Transform](../../../sceneview/io.github.sceneview.math/-transform/index.md) |
| [xDirection](x-direction.md) | [androidJvm]<br>val Pose.[xDirection](x-direction.md): [Direction](../../../sceneview/io.github.sceneview.math/-direction/index.md) |
| [yDirection](y-direction.md) | [androidJvm]<br>val Pose.[yDirection](y-direction.md): [Direction](../../../sceneview/io.github.sceneview.math/-direction/index.md) |
| [zDirection](z-direction.md) | [androidJvm]<br>val Pose.[zDirection](z-direction.md): [Direction](../../../sceneview/io.github.sceneview.math/-direction/index.md) |
