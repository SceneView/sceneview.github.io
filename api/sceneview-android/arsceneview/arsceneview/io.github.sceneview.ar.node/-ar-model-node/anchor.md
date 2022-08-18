//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArModelNode](index.md)/[anchor](anchor.md)

# anchor

[androidJvm]\
open fun [anchor](anchor.md)(): Anchor?

###  Anchor this node to make it fixed at the actual position and orientation is the world

Creates an anchor at the given pose in the world coordinate space that is attached to this trackable. The type of trackable will determine the semantics of attachment and how the anchor's pose will be updated to maintain this relationship. Note that the relative offset between the pose of multiple anchors attached to a trackable may adjust slightly over time as ARCore updates its model of the world.

#### Return

the created anchor or nullif the node could not be anchored
