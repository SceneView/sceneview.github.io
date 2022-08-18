//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ModelRenderable](index.md)

# ModelRenderable

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

open class [ModelRenderable](index.md) : [Renderable](../-renderable/index.md)

Renders a 3D Model by attaching it to a com.google.ar.sceneform.Node with setRenderable. 

future = ModelRenderable.builder().setSource(context, R.raw.renderable).build();
renderable = future.thenAccept(...);

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md) : [Renderable.Builder](../-renderable/-builder/index.md)&lt;[ModelRenderable](index.md), [ModelRenderable.Builder](-builder/index.md)&gt; <br>Factory class for [ModelRenderable](index.md). |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [ModelRenderable.Builder](-builder/index.md)<br>Constructs a [ModelRenderable](index.md). |
| [createInstance](../-renderable/create-instance.md) | [androidJvm]<br>open fun [createInstance](../-renderable/create-instance.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)): [RenderableInstance](../-renderable-instance/index.md) |
| [getAnimationFrameRate](../-view-renderable/index.md#1928215303%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getAnimationFrameRate](../-view-renderable/index.md#1928215303%2FFunctions%2F-1571379623)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the number of frames per seconds defined in the asset animation. |
| [getCollisionShape](../-view-renderable/index.md#111252609%2FFunctions%2F-1571379623) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getCollisionShape](../-view-renderable/index.md#111252609%2FFunctions%2F-1571379623)(): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md)<br>Get the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [getFinalModelMatrix](../-renderable/get-final-model-matrix.md) | [androidJvm]<br>open fun [getFinalModelMatrix](../-renderable/get-final-model-matrix.md)(originalMatrix: [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)<br>Gets the final model matrix to use for rendering this [Renderable](../-renderable/index.md) based on the matrix passed in. |
| [getId](../-renderable/get-id.md) | [androidJvm]<br>open fun [getId](../-renderable/get-id.md)(): [ChangeId](../../com.google.ar.sceneform.utilities/-change-id/index.md) |
| [getMaterial](../-renderable/get-material.md) | [androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(): MaterialInstance<br>Returns the material bound to the first submesh.<br>[androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): MaterialInstance<br>Returns the material bound to the specified submesh. |
| [getRenderPriority](../-view-renderable/index.md#-737854186%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getRenderPriority](../-view-renderable/index.md#-737854186%2FFunctions%2F-1571379623)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get the render priority that controls the order of rendering. |
| [getSubmeshCount](../-renderable/get-submesh-count.md) | [androidJvm]<br>open fun [getSubmeshCount](../-renderable/get-submesh-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of submeshes that this renderable has. |
| [getSubmeshName](../-renderable/get-submesh-name.md) | [androidJvm]<br>open fun [getSubmeshName](../-renderable/get-submesh-name.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the name associated with the specified submesh. |
| [isShadowCaster](../-renderable/is-shadow-caster.md) | [androidJvm]<br>open fun [isShadowCaster](../-renderable/is-shadow-caster.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if configured to cast shadows on other renderables. |
| [isShadowReceiver](../-renderable/is-shadow-receiver.md) | [androidJvm]<br>open fun [isShadowReceiver](../-renderable/is-shadow-receiver.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if configured to receive shadows cast by other renderables. |
| [makeCopy](make-copy.md) | [androidJvm]<br>open fun [makeCopy](make-copy.md)(): [ModelRenderable](index.md)<br>Creates a new instance of this ModelRenderable. |
| [prepareForDraw](../-renderable/prepare-for-draw.md) | [androidJvm]<br>open fun [prepareForDraw](../-renderable/prepare-for-draw.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md))<br>Optionally override in subclasses for work that must be done each frame for specific types of Renderables. |
| [setCollisionShape](../-view-renderable/index.md#1712308023%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setCollisionShape](../-view-renderable/index.md#1712308023%2FFunctions%2F-1571379623)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)collisionShape: [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md))<br>Set the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [setMaterial](../-renderable/set-material.md) | [androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(material: MaterialInstance)<br>Sets the material bound to the first submesh.<br>[androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), material: MaterialInstance)<br>Sets the material bound to the specified submesh. |
| [setRenderPriority](../-view-renderable/index.md#-1128078807%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setRenderPriority](../-view-renderable/index.md#-1128078807%2FFunctions%2F-1571379623)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = "", to = "")renderPriority: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Set the render priority to control the order of rendering. |
| [setShadowCaster](../-renderable/set-shadow-caster.md) | [androidJvm]<br>open fun [setShadowCaster](../-renderable/set-shadow-caster.md)(isShadowCaster: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets whether the renderable casts shadow on other renderables in the scene. |
| [setShadowReceiver](../-renderable/set-shadow-receiver.md) | [androidJvm]<br>open fun [setShadowReceiver](../-renderable/set-shadow-receiver.md)(isShadowReceiver: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets whether the renderable receives shadows cast by other renderables in the scene. |
| [updateFromDefinition](../-renderable/update-from-definition.md) | [androidJvm]<br>open fun [updateFromDefinition](../-renderable/update-from-definition.md)(definition: [RenderableDefinition](../-renderable-definition/index.md)) |
