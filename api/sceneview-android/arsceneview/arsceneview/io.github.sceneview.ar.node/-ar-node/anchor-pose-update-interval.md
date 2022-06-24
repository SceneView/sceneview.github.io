//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[anchorPoseUpdateInterval](anchor-pose-update-interval.md)

# anchorPoseUpdateInterval

[androidJvm]\
var [anchorPoseUpdateInterval](anchor-pose-update-interval.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null

###  Adjust the anchor pose update interval in seconds

ARCore may update the [anchor](anchor.md) pose because of environment detection evolving during time. You can choose to retrieve more accurate anchor position and rotation or let it as it was when it was anchored. Only used when the [ArNode](index.md) is anchored. null means never update the pose
