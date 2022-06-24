//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[onTapAr](on-tap-ar.md)

# onTapAr

[androidJvm]\
open fun [onTapAr](on-tap-ar.md)(hitResult: HitResult, motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))

###  Invoked when an ARCore trackable is tapped

Calls the onTapAr listener if it is available.

## Parameters

androidJvm

| | |
|---|---|
| hitResult | The ARCore hit result for the trackable that was tapped. |
| motionEvent | The motion event that caused the tap. |

[androidJvm]\
var [onTapAr](on-tap-ar.md): (hitResult: HitResult, motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when an ARCore trackable is tapped

Depending on the session configuration the HitResult.getTrackable can be:

- 
   A Plane if [ArSession.planeFindingEnabled](../../io.github.sceneview.ar.arcore/-ar-session/plane-finding-enabled.md).
- 
   An InstantPlacementPoint if [ArSession.instantPlacementEnabled](../../io.github.sceneview.ar.arcore/-ar-session/instant-placement-enabled.md).
- 
   A DepthPoint and Point if [ArSession.depthEnabled](../../io.github.sceneview.ar.arcore/-ar-session/depth-enabled.md).

The listener is only invoked if no node is tapped.

- 
   hitResult - The ARCore hit result for the trackable that was tapped.
- 
   motionEvent - The motion event that caused the tap.
