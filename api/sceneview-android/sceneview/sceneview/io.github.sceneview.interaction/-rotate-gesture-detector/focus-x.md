//[sceneview](../../../index.md)/[io.github.sceneview.interaction](../index.md)/[RotateGestureDetector](index.md)/[focusX](focus-x.md)

# focusX

[androidJvm]\
var [focusX](focus-x.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null

###  The X coordinate of the current gesture's focal point in pixels

If a gesture is in progress, the focal point is between each of the pointers forming the gesture. If a gesture is ending, the focal point is the location of the  remaining pointer on the screen. If [isGestureInProgress](is-gesture-in-progress.md) would return false, the result of this function is null.
