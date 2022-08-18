//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[pose](pose.md)

# pose

[androidJvm]\
open var [pose](pose.md): Pose? = null

###  The position of the intersection between a ray and detected real-world geometry.

The position is the location in space where the ray intersected the geometry. The orientation is a best effort to face the user's device, and its exact definition differs depending on the Trackable that was hit.

- 
   Plane: X+ is perpendicular to the cast ray and parallel to the plane, Y+ points along the plane normal (up, for Plane.Type.HORIZONTAL_UPWARD_FACING planes), and Z+ is parallel to the plane, pointing roughly toward the user's device.
- 
   Point: Attempt to estimate the normal of the surface centered around the hit test. Surface normal estimation is most likely to succeed on textured surfaces and with camera motion. If Point.getOrientationMode returns Point.OrientationMode.ESTIMATED_SURFACE_NORMAL, then X+ is perpendicular to the cast ray and parallel to the physical surface centered around the hit test, Y+ points along the estimated surface normal, and Z+ points roughly toward the user's device. If Point.getOrientationMode returns Point.OrientationMode.INITIALIZED_TO_IDENTITY, then X+ is perpendicular to the cast ray and points right from the perspective of the user's device, Y+ points up, and Z+ points roughly toward the user's device.
- 
   If you wish to retain the location of this pose beyond the duration of a single frame, create an Anchor using [createAnchor](../../io.github.sceneview.ar.arcore/create-anchor.md) to save the pose in a physically consistent way.

## See also

androidJvm

| | |
|---|---|
| [createAnchor](../../io.github.sceneview.ar.arcore/create-anchor.md) |  |
