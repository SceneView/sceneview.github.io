//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[onTouchAr](on-touch-ar.md)

# onTouchAr

[androidJvm]\
var [onTouchAr](on-touch-ar.md): (hitResult: HitResult, motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null

###  Invoked when an ARCore plane is tapped

Registers a callback to be invoked when an ARCore Trackable is tapped. Depending on the session config you defined, the HitResult.getTrackable can be:

- 
   a Plane if [ArSession.planeFindingEnabled](../../io.github.sceneview.ar.arcore/-ar-session/plane-finding-enabled.md)
- 
   an InstantPlacementPoint if [ArSession.instantPlacementEnabled](../../io.github.sceneview.ar.arcore/-ar-session/instant-placement-enabled.md)
- 
   a DepthPoint if [ArSession.depthEnabled](../../io.github.sceneview.ar.arcore/-ar-session/depth-enabled.md)

The callback will only be invoked if no com.google.ar.sceneform.Node was tapped.

- 
   hitResult: The ARCore hit result that occurred when tapping the plane
- 
   motionEvent: the motion event that triggered the tap
