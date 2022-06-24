//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)/[shouldBeRendered](should-be-rendered.md)

# shouldBeRendered

[androidJvm]\
open val [shouldBeRendered](should-be-rendered.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  The active status

A node is considered active if it meets ALL of the following conditions:

- 
   The node is part of a scene.
- 
   the node's parent is active.
- 
   The node is enabled.

An active Node has the following behavior:

- 
   The node's [onFrame](on-frame.md) function will be called every frame.
- 
   The node's [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623) will be rendered.
- 
   The node's [collisionShape](collision-shape.md) will be checked in calls to Scene.hitTest.
- 
   The node's onTouchEvent function will be called when the node is touched.
