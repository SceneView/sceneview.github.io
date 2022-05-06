//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[Renderable](index.md)

# Renderable

[androidJvm]\
abstract class [Renderable](index.md)

Base class for rendering in 3D space by attaching to a [io.github.sceneview.node.Node](../../io.github.sceneview.node/-node/index.md) with setModel.

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>abstract class [Builder](-builder/index.md)&lt;[T](-builder/index.md) : [Renderable](index.md)?, [B](-builder/index.md) : [Renderable.Builder](-builder/index.md)&lt;[T](../-load-renderable-from-filament-gltf-task/index.md), [B](-builder/index.md)&gt;?&gt;<br>Used to programmatically construct a [Renderable](index.md). |

## Functions

| Name | Summary |
|---|---|
| [createInstance](create-instance.md) | [androidJvm]<br>open fun [createInstance](create-instance.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)): [RenderableInstance](../-renderable-instance/index.md) |
| [getFinalModelMatrix](get-final-model-matrix.md) | [androidJvm]<br>open fun [getFinalModelMatrix](get-final-model-matrix.md)(originalMatrix: [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)<br>Gets the final model matrix to use for rendering this [Renderable](index.md) based on the matrix passed in. |
| [getId](get-id.md) | [androidJvm]<br>open fun [getId](get-id.md)(): [ChangeId](../../com.google.ar.sceneform.utilities/-change-id/index.md) |
| [getMaterial](get-material.md) | [androidJvm]<br>open fun [getMaterial](get-material.md)(): [Material](../-material/index.md)<br>Returns the material bound to the first submesh.<br>[androidJvm]<br>open fun [getMaterial](get-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Material](../-material/index.md)<br>Returns the material bound to the specified submesh. |
| [getSubmeshCount](get-submesh-count.md) | [androidJvm]<br>open fun [getSubmeshCount](get-submesh-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of submeshes that this renderable has. |
| [getSubmeshName](get-submesh-name.md) | [androidJvm]<br>open fun [getSubmeshName](get-submesh-name.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the name associated with the specified submesh. |
| [makeCopy](make-copy.md) | [androidJvm]<br>abstract fun [makeCopy](make-copy.md)(): [Renderable](index.md)<br>Creates a new instance of this Renderable. |
| [setMaterial](set-material.md) | [androidJvm]<br>open fun [setMaterial](set-material.md)(material: [Material](../-material/index.md))<br>Sets the material bound to the first submesh.<br>[androidJvm]<br>open fun [setMaterial](set-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), material: [Material](../-material/index.md))<br>Sets the material bound to the specified submesh. |
| [setShadowCaster](set-shadow-caster.md) | [androidJvm]<br>open fun [setShadowCaster](set-shadow-caster.md)(isShadowCaster: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets whether the renderable casts shadow on other renderables in the scene. |
| [setShadowReceiver](set-shadow-receiver.md) | [androidJvm]<br>open fun [setShadowReceiver](set-shadow-receiver.md)(isShadowReceiver: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets whether the renderable receives shadows cast by other renderables in the scene. |
| [updateFromDefinition](update-from-definition.md) | [androidJvm]<br>open fun [updateFromDefinition](update-from-definition.md)(definition: [RenderableDefinition](../-renderable-definition/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [animationFrameRate](animation-frame-rate.md) | [androidJvm]<br>private open val [animationFrameRate](animation-frame-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [collisionShape](collision-shape.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>@get:[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>protected open var [collisionShape](collision-shape.md): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) |
| [DEFAULT_ANIMATION_FRAME_RATE](-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md) | [androidJvm]<br>val [DEFAULT_ANIMATION_FRAME_RATE](-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isShadowCaster](is-shadow-caster.md) | [androidJvm]<br>private open val [isShadowCaster](is-shadow-caster.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isShadowReceiver](is-shadow-receiver.md) | [androidJvm]<br>private open val [isShadowReceiver](is-shadow-receiver.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [RENDER_PRIORITY_DEFAULT](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_DEFAULT](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_FIRST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_FIRST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_LAST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_LAST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [renderPriority](render-priority.md) | [androidJvm]<br>private open var [renderPriority](render-priority.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [ModelRenderable](../-model-renderable/index.md) |
| [ViewRenderable](../-view-renderable/index.md) |
