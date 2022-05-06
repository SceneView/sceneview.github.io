//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[isDepthOcclusionEnabled](is-depth-occlusion-enabled.md)

# isDepthOcclusionEnabled

[androidJvm]\
var [isDepthOcclusionEnabled](is-depth-occlusion-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

###  Enable the depth occlusion material

This will process the incoming DepthImage to occlude virtual objects behind real world objects.

If the Session is not configured properly the standard camera material is used. Valid Session configuration for the DepthMode are Config.DepthMode.AUTOMATIC and Config.DepthMode.RAW_DEPTH_ONLY

Disable this value to apply the standard camera material to the CameraStream.
