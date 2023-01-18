//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ViewRenderable](index.md)

# ViewRenderable

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

open class [ViewRenderable](index.md) : [Renderable](../-renderable/index.md)

Renders a 2D Android view in 3D space by attaching it to a [Node](../../io.github.sceneview.node/-node/index.md) with setModel. By default, the size of the view is 1 meter in the [SceneView](../../io.github.sceneview/-scene-view/index.md) per 250dp in the layout. Use a [ViewSizer](../-view-sizer/index.md) to control how the size of the view in the  is calculated. 

```kotlin

future = ViewRenderable.builder().setView(context, R.layout.view).build();
viewRenderable = future.thenAccept(...);

```

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [androidJvm]<br>class [Builder](-builder/index.md) : [Renderable.Builder](../-renderable/-builder/index.md)&lt;[T](../-renderable/-builder/index.md), [B](../-renderable/-builder/index.md)&gt; <br>Factory class for [ViewRenderable](index.md) |
| [HorizontalAlignment](-horizontal-alignment/index.md) | [androidJvm]<br>enum [HorizontalAlignment](-horizontal-alignment/index.md)<br>Controls the horizontal alignment of the [ViewRenderable](index.md) relative to the  it is attached to. |
| [VerticalAlignment](-vertical-alignment/index.md) | [androidJvm]<br>enum [VerticalAlignment](-vertical-alignment/index.md)<br>Controls the vertical alignment of the [ViewRenderable](index.md) relative to the  it is attached to. |

## Functions

| Name | Summary |
|---|---|
| [attachView](attach-view.md) | [androidJvm]<br>open fun [attachView](attach-view.md)(attachmentManager: [ViewAttachmentManager](../-view-attachment-manager/index.md)) |
| [builder](builder.md) | [androidJvm]<br>open fun [builder](builder.md)(): [ViewRenderable.Builder](-builder/index.md)<br>Constructs a [ViewRenderable](index.md) |
| [convertWorldPositionToLocalView](convert-world-position-to-local-view.md) | [androidJvm]<br>open fun [convertWorldPositionToLocalView](convert-world-position-to-local-view.md)(node: [Node](../../io.github.sceneview.node/-node/index.md), worldPos: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [createInstance](../-renderable/create-instance.md) | [androidJvm]<br>open fun [createInstance](../-renderable/create-instance.md)(transformProvider: [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md)): [RenderableInstance](../-renderable-instance/index.md) |
| [detachView](detach-view.md) | [androidJvm]<br>open fun [detachView](detach-view.md)() |
| [dispatchTouchEventToView](dispatch-touch-event-to-view.md) | [androidJvm]<br>open fun [dispatchTouchEventToView](dispatch-touch-event-to-view.md)(@NotNullnode: [Node](../../io.github.sceneview.node/-node/index.md), @NotNullmotionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Dispatches a touch event to a node's ViewRenderable if that node has a ViewRenderable by converting the touch event into the local coordinate space of the view. |
| [getCollisionShape](../-renderable/get-collision-shape.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getCollisionShape](../-renderable/get-collision-shape.md)(): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md)<br>Get the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [getFinalModelMatrix](get-final-model-matrix.md) | [androidJvm]<br>open fun [getFinalModelMatrix](get-final-model-matrix.md)(originalMatrix: [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)<br>Takes the model matrix from the [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md) for rendering this  and scales it to size it appropriately based on the meters to pixel ratio for the view. |
| [getId](../-renderable/get-id.md) | [androidJvm]<br>open fun [getId](../-renderable/get-id.md)(): [ChangeId](../../com.google.ar.sceneform.utilities/-change-id/index.md) |
| [getMaterial](../-renderable/get-material.md) | [androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(): MaterialInstance<br>Returns the material bound to the first submesh.<br>[androidJvm]<br>open fun [getMaterial](../-renderable/get-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): MaterialInstance<br>Returns the material bound to the specified submesh. |
| [getSizer](get-sizer.md) | [androidJvm]<br>open fun [getSizer](get-sizer.md)(): [ViewSizer](../-view-sizer/index.md)<br>Gets the [ViewSizer](../-view-sizer/index.md) that controls the size of this [ViewRenderable](index.md) in the . |
| [getSubmeshCount](../-renderable/get-submesh-count.md) | [androidJvm]<br>open fun [getSubmeshCount](../-renderable/get-submesh-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Returns the number of submeshes that this renderable has. |
| [getSubmeshName](../-renderable/get-submesh-name.md) | [androidJvm]<br>open fun [getSubmeshName](../-renderable/get-submesh-name.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the name associated with the specified submesh. |
| [makeCopy](make-copy.md) | [androidJvm]<br>open fun [makeCopy](make-copy.md)(): [ViewRenderable](index.md)<br>Creates a new instance of this ViewRenderable. |
| [prepareForDraw](prepare-for-draw.md) | [androidJvm]<br>open fun [prepareForDraw](prepare-for-draw.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md)) |
| [setCollisionShape](../-renderable/set-collision-shape.md) | [androidJvm]<br>open fun [setCollisionShape](../-renderable/set-collision-shape.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)collisionShape: [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md))<br>Set the [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md) used for collision detection with this [Renderable](../-renderable/index.md). |
| [setMaterial](../-renderable/set-material.md) | [androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(material: MaterialInstance)<br>Sets the material bound to the first submesh.<br>[androidJvm]<br>open fun [setMaterial](../-renderable/set-material.md)(submeshIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), material: MaterialInstance)<br>Sets the material bound to the specified submesh. |
| [setSizer](set-sizer.md) | [androidJvm]<br>open fun [setSizer](set-sizer.md)(viewSizer: [ViewSizer](../-view-sizer/index.md))<br>Sets the [ViewSizer](../-view-sizer/index.md) that controls the size of this [ViewRenderable](index.md) in the . |
| [updateFromDefinition](../-renderable/update-from-definition.md) | [androidJvm]<br>open fun [updateFromDefinition](../-renderable/update-from-definition.md)(definition: [RenderableDefinition](../-renderable-definition/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [animationFrameRate](../-renderable/animation-frame-rate.md) | [androidJvm]<br>open val [animationFrameRate](../-renderable/animation-frame-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [DEFAULT_ANIMATION_FRAME_RATE](../-renderable/-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md) | [androidJvm]<br>val [DEFAULT_ANIMATION_FRAME_RATE](../-renderable/-d-e-f-a-u-l-t_-a-n-i-m-a-t-i-o-n_-f-r-a-m-e_-r-a-t-e.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [horizontalAlignment](horizontal-alignment.md) | [androidJvm]<br>open var [horizontalAlignment](horizontal-alignment.md): [ViewRenderable.HorizontalAlignment](-horizontal-alignment/index.md) |
| [isShadowCaster](../-renderable/is-shadow-caster.md) | [androidJvm]<br>open var [isShadowCaster](../-renderable/is-shadow-caster.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isShadowReceiver](../-renderable/is-shadow-receiver.md) | [androidJvm]<br>open var [isShadowReceiver](../-renderable/is-shadow-receiver.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [RENDER_PRIORITY_DEFAULT](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_DEFAULT](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_FIRST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_FIRST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RENDER_PRIORITY_LAST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md) | [androidJvm]<br>val [RENDER_PRIORITY_LAST](../-renderable/-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [renderPriority](../-renderable/render-priority.md) | [androidJvm]<br>open var [renderPriority](../-renderable/render-priority.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [verticalAlignment](vertical-alignment.md) | [androidJvm]<br>open var [verticalAlignment](vertical-alignment.md): [ViewRenderable.VerticalAlignment](-vertical-alignment/index.md) |
| [view](view.md) | [androidJvm]<br>val [view](view.md): [View](https://developer.android.com/reference/kotlin/android/view/View.html) |
| [viewRenderableData](view-renderable-data.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open var [viewRenderableData](view-renderable-data.md): [ViewRenderableInternalData](../-view-renderable-internal-data/index.md) |
