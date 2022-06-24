//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[rotation](rotation.md)

# rotation

[androidJvm]\
var [rotation](rotation.md): [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623)

###  The node orientation in Euler Angles Degrees per axis from 0.0f to 360.0f

The three-component rotation vector specifies the direction of the rotation axis in degrees. Rotation is applied relative to the node's origin property.

Default is Rotation(x = 0.0f, y = 0.0f, z = 0.0f), specifying no rotation.

Note that modifying the individual components of the returned rotation doesn't have any effect.

------- +y ----- -z

---------|----/----

---------|--/------

-x - - - 0 - - - +x

------/--|---------

----/----|---------

+z ---- -y --------
