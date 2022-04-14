//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArFrame](index.md)

# ArFrame

[androidJvm]\
data class [ArFrame](index.md)(session: [ArSession](../-ar-session/index.md), time: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), frame: Frame)

###  Captures the state and changes to the AR system from a call to [Session.update](../-ar-session/index.md#-765428480%2FFunctions%2F-58641720)

## Constructors

| | |
|---|---|
| [ArFrame](-ar-frame.md) | [androidJvm]<br>fun [ArFrame](-ar-frame.md)(session: [ArSession](../-ar-session/index.md), time: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md), frame: Frame) |

## Functions

| Name | Summary |
|---|---|
| [createAnchor](create-anchor.md) | [androidJvm]<br>fun [createAnchor](create-anchor.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): Anchor?<br>See [hitTests](hit-tests.md) and com.google.ar.core.HitResult.getHitPose for details. Anchors incur ongoing processing overhead within ARCore. To release unneeded anchors use Anchor#detach(). |
| [fps](fps.md) | [androidJvm]<br>fun [fps](fps.md)(arFrame: [ArFrame](index.md)?): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hitTest](hit-test.md) | [androidJvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [hitTest](hit-test.md)(motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html), approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): HitResult?<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [hitTest](hit-test.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): HitResult? |
| [hitTests](hit-tests.md) | [androidJvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [hitTests](hit-tests.md)(xPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayWidth / 2.0f, yPx: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.displayHeight / 2.0f, approximateDistanceMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = session.approximateDistanceMeters, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.planeFindingEnabled, depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.depthEnabled, instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = session.instantPlacementEnabled): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;HitResult&gt;<br>Performs a ray cast from the user's device in the direction of the given location in the camera view. Intersections with detected scene geometry are returned, sorted by distance from the device; the nearest intersection is returned first. |
| [precision](precision.md) | [androidJvm]<br>fun [precision](precision.md)(arFrame: [ArFrame](index.md)?): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Properties

| Name | Summary |
|---|---|
| [camera](camera.md) | [androidJvm]<br>val [camera](camera.md): Camera |
| [fps](fps.md) | [androidJvm]<br>val [fps](fps.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [frame](frame.md) | [androidJvm]<br>val [frame](frame.md): Frame |
| [isTrackingAugmentedFace](is-tracking-augmented-face.md) | [androidJvm]<br>val [isTrackingAugmentedFace](is-tracking-augmented-face.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTrackingAugmentedImage](is-tracking-augmented-image.md) | [androidJvm]<br>val [isTrackingAugmentedImage](is-tracking-augmented-image.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isTrackingPlane](is-tracking-plane.md) | [androidJvm]<br>val [isTrackingPlane](is-tracking-plane.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [session](session.md) | [androidJvm]<br>val [session](session.md): [ArSession](../-ar-session/index.md) |
| [time](time.md) | [androidJvm]<br>val [time](time.md): [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md) |
| [updatedAugmentedFaces](updated-augmented-faces.md) | [androidJvm]<br>val [updatedAugmentedFaces](updated-augmented-faces.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;AugmentedFace&gt; |
| [updatedAugmentedImages](updated-augmented-images.md) | [androidJvm]<br>val [updatedAugmentedImages](updated-augmented-images.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;AugmentedImage&gt; |
| [updatedPlanes](updated-planes.md) | [androidJvm]<br>val [updatedPlanes](updated-planes.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Plane&gt; |
| [updatedTrackables](updated-trackables.md) | [androidJvm]<br>val [updatedTrackables](updated-trackables.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Trackable&gt; |
