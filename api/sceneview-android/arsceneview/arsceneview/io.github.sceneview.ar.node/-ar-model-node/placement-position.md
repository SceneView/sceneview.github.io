//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[placementPosition](placement-position.md)

# placementPosition

[androidJvm]\
var [placementPosition](placement-position.md): [Position](../../../../sceneview/io.github.sceneview.math/-position/index.md)

###  The node camera/screen position

- 
   While there is no AR tracking information available, the node is following the camera moves so it stays at this camera/screen relative position [com.google.ar.sceneform.Camera](../../../../arsceneview/com.google.ar.sceneform/-camera/index.md) node is considered as the parent
- 
   ARCore will try to find the real world position of this screen position and the node [io.github.sceneview.node.Node.worldPosition](../../io.github.sceneview.ar.node.infos/-tap-ar-plane-info-node/index.md#-1871817086%2FProperties%2F-58641720) will be updated so.

The Z value is only used when no surface is actually detected or when instant placement is enabled:

- 
   In case of instant placement disabled, the z position will be estimated by the AR surface distance at the (x,y) so this value is not used.
- 
   In case of instant placement enabled, this value is used as [approximateDistanceMeters](../../io.github.sceneview.ar.arcore/-ar-frame/hit-test.md) to help ARCore positioning result.

By default, the node is positioned at the center screen, 2 meters forward

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
