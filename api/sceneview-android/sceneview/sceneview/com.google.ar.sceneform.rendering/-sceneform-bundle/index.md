//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[SceneformBundle](index.md)

# SceneformBundle

[androidJvm]\
class [SceneformBundle](index.md)

Helper functions for loading and processing rendercore bundles.

## Functions

| Name | Summary |
|---|---|
| [isSceneformBundle](is-sceneform-bundle.md) | [androidJvm]<br>open fun [isSceneformBundle](is-sceneform-bundle.md)(buffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [readCollisionGeometry](read-collision-geometry.md) | [androidJvm]<br>open fun [readCollisionGeometry](read-collision-geometry.md)(rcb: SceneformBundleDef): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) |
| [tryLoadSceneformBundle](try-load-sceneform-bundle.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [tryLoadSceneformBundle](try-load-sceneform-bundle.md)(buffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): SceneformBundleDef |

## Properties

| Name | Summary |
|---|---|
| [RCB_MAJOR_VERSION](-r-c-b_-m-a-j-o-r_-v-e-r-s-i-o-n.md) | [androidJvm]<br>val [RCB_MAJOR_VERSION](-r-c-b_-m-a-j-o-r_-v-e-r-s-i-o-n.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [RCB_MINOR_VERSION](-r-c-b_-m-i-n-o-r_-v-e-r-s-i-o-n.md) | [androidJvm]<br>val [RCB_MINOR_VERSION](-r-c-b_-m-i-n-o-r_-v-e-r-s-i-o-n.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
