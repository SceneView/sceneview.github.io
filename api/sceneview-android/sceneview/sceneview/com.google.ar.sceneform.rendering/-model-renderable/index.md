//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ModelRenderable](index.md)

# ModelRenderable

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

open class [ModelRenderable](index.md) : [Renderable](../-renderable/index.md)

Renders a 3D Model by attaching it to a com.google.ar.sceneform.Node with setRenderable. 

```kotlin

future = ModelRenderable.builder().setSource(context, R.raw.renderable).build();
renderable = future.thenAccept(...);

```

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md) : [Renderable.Builder](../-renderable/-builder/index.md)&lt;[T](../-renderable/-builder/index.md), [B](../-renderable/-builder/index.md)&gt; <br>Factory class for [ModelRenderable](index.md). |

## Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [ModelRenderable.Builder](-builder/index.md)<br>Constructs a [ModelRenderable](index.md). |
| [createInstance](../-renderable/create-instance.md) | [androidJvm]<br>open fun [createInstance](../-renderable/create-instance.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)): [RenderableInstance](../-renderable-instance/index.md) |
| [getCollisionShape](../-renderable/get-collision-shape.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getCollisionShape](../-renderable/get-collision-shape.md)(): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md)<br>Get the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [getFinalModelMatrix](../-renderable/get-final-model-matrix.md) | [androidJvm]<br>open fun [getFinalModelMatrix](../-renderable/get-final-model-matrix.md)(originalMatrix: [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)<br>Gets the final model matrix to use for rendering this [Renderable](../-renderable/index.md) based on the matrix passed in. |
| [getId](../-renderable/get-id.md) | [androidJvm]<br>open fun [getId](../-renderable/get-id.md)(): [ChangeId](../../com.google.ar.sceneform.utilities/-change-id/index.md) |
| [getMaterial](../-renderable/get-material.md) | [androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(): MaterialInstance<br>Returns the material bound to the first submesh.<br>[androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): MaterialInstance<br>Returns the material bound to the specified submesh. |
| [getSubmeshCount](../-renderable/get-submesh-count.md) | [androidJvm]<br>open fun [getSubmeshCount](../-renderable/get-submesh-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of submeshes that this renderable has. |
| [getSubmeshName](../-renderable/get-submesh-name.md) | [androidJvm]<br>open fun [getSubmeshName](../-renderable/get-submesh-name.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the name associated with the specified submesh. |
| [makeCopy](make-copy.md) | [androidJvm]<br>open fun [makeCopy](make-copy.md)(): [ModelRenderable](index.md)<br>Creates a new instance of this ModelRenderable. |
| [prepareForDraw](../-renderable/prepare-for-draw.md) | [androidJvm]<br>open fun [prepareForDraw](../-renderable/prepare-for-draw.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md))<br>Optionally override in subclasses for work that must be done each frame for specific types of Renderables. |
| [setCollisionShape](../-renderable/set-collision-shape.md) | [androidJvm]<br>open fun [setCollisionShape](../-renderable/set-collision-shape.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)collisionShape: [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md))<br>Set the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [setMaterial](../-renderable/set-material.md) | [androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(material: MaterialInstance)<br>Sets the material bound to the first submesh.<br>[androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), material: MaterialInstance)<br>Sets the material bound to the specified submesh. |
| [updateFromDefinition](../-renderable/update-from-definition.md) | [androidJvm]<br>open fun [updateFromDefinition](../-renderable/update-from-definition.md)(definition: [RenderableDefinition](../-renderable-definition/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [animationFrameRate](../-renderable/animation-frame-rate.md) | [androidJvm]<br>open val [animationFrameRate](../-renderable/animation-frame-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [DEFAULT_ANIMATION_FRAME_RATE](../-renderable/-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md) | [androidJvm]<br>val [DEFAULT_ANIMATION_FRAME_RATE](../-renderable/-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isShadowCaster](../-renderable/is-shadow-caster.md) | [androidJvm]<br>open var [isShadowCaster](../-renderable/is-shadow-caster.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isShadowReceiver](../-renderable/is-shadow-receiver.md) | [androidJvm]<br>open var [isShadowReceiver](../-renderable/is-shadow-receiver.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [RENDER_PRIORITY_DEFAULT](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_DEFAULT](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_FIRST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_FIRST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_LAST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_LAST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [renderPriority](../-renderable/render-priority.md) | [androidJvm]<br>open var [renderPriority](../-renderable/render-priority.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
