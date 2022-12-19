//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[TransformComponent](index.md)/[position](position.md)

# position

[androidJvm]\
open var [position](position.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)

Position to locate within the coordinate system the parent.

Default is `Position(x = 0.0f, y = 0.0f, z = 0.0f)`, indicating that the component is placed at the origin of the parent component's coordinate system.

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
| [io.github.sceneview.components.TransformComponent](transform.md) |  |
