//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[hitPosition](hit-position.md)

# hitPosition

[androidJvm]\
var [hitPosition](hit-position.md): [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md)

###  The node camera/screen/view position where the hit will be made to find an AR position

Until it is anchored, the Node will try to find the real world position/orientation of the screen coordinate and constantly place/orientate himself accordingly if [followHitPosition](follow-hit-position.md) is `true`

The Z value is only used when no surface is actually detected or when [followHitPosition](follow-hit-position.md) and [instantAnchor](instant-anchor.md) is set to `false` or when instant placement is enabled:

- 
   In case of instant placement disabled, the z position (distance from the camera) will be estimated by the AR surface distance at the (x,y) so this value is not used.
- 
   In case of instant placement enabled, this value is used as an approximateDistanceMeters at the [ArFrame.hitTest](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) call to help ARCore positioning the result quickly.

By default, the node is positioned at the center screen, 4 meters forward

**Horizontal (X):**

- 
   left: x < 0.0f
- 
   center horizontal: x = 0.0f
- 
   right: x 0.0f

**Vertical (Y):**

- 
   top: y 0.0f
- 
   center vertical : y = 0.0f
- 
   bottom: y < 0.0f

**Depth (Z):**

- 
   forward: z < 0.0f
- 
   origin/camera position: z = 0.0f
- 
   backward: z 0.0f

------- +y ----- -z

---------|----/----

---------|--/------

-x - - - 0 - - - +x

------/--|---------

----/----|---------

+z ---- -y --------

## See also

androidJvm

| | |
|---|---|
| [io.github.sceneview.ar.node.ArModelNode](follow-hit-position.md) |  |
