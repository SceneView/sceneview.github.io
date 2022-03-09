//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[position](position.md)

# position

[androidJvm]\
var [position](position.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)

###  The node position

The node's position locates it within the coordinate system of its parent. The default position is the zero vector, indicating that the node is placed at the origin of the parent node's coordinate system.

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
