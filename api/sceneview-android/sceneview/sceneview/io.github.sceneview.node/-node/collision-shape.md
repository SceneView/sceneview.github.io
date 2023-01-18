//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[collisionShape](collision-shape.md)

# collisionShape

[androidJvm]\
var [collisionShape](collision-shape.md): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md)? = null

###  The shape to used to detect collisions for this [Node](index.md)

If the shape is not set and renderable is set, then Renderable.getCollisionShape is used to detect collisions for this [Node](index.md).

[CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) represents a geometric shape, i.e. sphere, box, convex hull. If null, this node's current collision shape will be removed.
