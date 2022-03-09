//[arsceneview](../../../index.md)/[io.github.sceneview.ar.arcore](../index.md)/[ArSession](index.md)/[currentFrame](current-frame.md)

# currentFrame

[androidJvm]\
var [currentFrame](current-frame.md): [ArFrame](../-ar-frame/index.md)? = null

###  The most recent ARCore Frame if it is available

The frame is updated at the beginning of each drawing frame. Callers of this method should not retain a reference to the return value, since it will be invalid to use the ARCore frame starting with the next frame.
