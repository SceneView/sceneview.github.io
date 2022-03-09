//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[RenderableInternalFilamentAssetData](index.md)

# RenderableInternalFilamentAssetData

[androidJvm]\
open class [RenderableInternalFilamentAssetData](index.md) : [IRenderableInternalData](../../../../arsceneview/com.google.ar.sceneform.rendering/-i-renderable-internal-data/index.md)

Represents the data used by a [Renderable](../-renderable/index.md) for rendering natively loaded glTF data.

## Functions

| Name | Summary |
|---|---|
| [buildInstanceData](build-instance-data.md) | [androidJvm]<br>open fun [buildInstanceData](build-instance-data.md)(instance: [RenderableInstance](../-renderable-instance/index.md), renderedEntity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [dispose](dispose.md) | [androidJvm]<br>open fun [dispose](dispose.md)()<br>Removes any memory used by the object. |
| [getAnimationNames](get-animation-names.md) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [getAnimationNames](get-animation-names.md)(): [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt; |
| [getCenterAabb](get-center-aabb.md) | [androidJvm]<br>open fun [getCenterAabb](get-center-aabb.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getExtentsAabb](get-extents-aabb.md) | [androidJvm]<br>open fun [getExtentsAabb](get-extents-aabb.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getIndexBuffer](get-index-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getIndexBuffer](get-index-buffer.md)(): IndexBuffer |
| [getMaterialBindingIds](get-material-binding-ids.md) | [androidJvm]<br>open fun [getMaterialBindingIds](get-material-binding-ids.md)(): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)&gt; |
| [getMeshes](get-meshes.md) | [androidJvm]<br>open fun [getMeshes](get-meshes.md)(): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[RenderableInternalData.MeshData](../../../../arsceneview/com.google.ar.sceneform.rendering/-renderable-internal-data/-mesh-data/index.md)&gt; |
| [getRawColorBuffer](get-raw-color-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getRawColorBuffer](get-raw-color-buffer.md)(): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html) |
| [getRawIndexBuffer](get-raw-index-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getRawIndexBuffer](get-raw-index-buffer.md)(): [IntBuffer](https://developer.android.com/reference/kotlin/java/nio/IntBuffer.html) |
| [getRawPositionBuffer](get-raw-position-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getRawPositionBuffer](get-raw-position-buffer.md)(): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html) |
| [getRawTangentsBuffer](get-raw-tangents-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getRawTangentsBuffer](get-raw-tangents-buffer.md)(): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html) |
| [getRawUvBuffer](get-raw-uv-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getRawUvBuffer](get-raw-uv-buffer.md)(): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html) |
| [getSizeAabb](get-size-aabb.md) | [androidJvm]<br>open fun [getSizeAabb](get-size-aabb.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getTransformOffset](get-transform-offset.md) | [androidJvm]<br>open fun [getTransformOffset](get-transform-offset.md)(): [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md) |
| [getTransformScale](get-transform-scale.md) | [androidJvm]<br>open fun [getTransformScale](get-transform-scale.md)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getVertexBuffer](get-vertex-buffer.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [getVertexBuffer](get-vertex-buffer.md)(): VertexBuffer |
| [setAnimationNames](set-animation-names.md) | [androidJvm]<br>open fun [setAnimationNames](set-animation-names.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)animationNames: [List](https://developer.android.com/reference/kotlin/java/util/List.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;) |
| [setCenterAabb](set-center-aabb.md) | [androidJvm]<br>open fun [setCenterAabb](set-center-aabb.md)(center: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)) |
| [setExtentsAabb](set-extents-aabb.md) | [androidJvm]<br>open fun [setExtentsAabb](set-extents-aabb.md)(halfExtents: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)) |
| [setIndexBuffer](set-index-buffer.md) | [androidJvm]<br>open fun [setIndexBuffer](set-index-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)indexBuffer: IndexBuffer) |
| [setRawColorBuffer](set-raw-color-buffer.md) | [androidJvm]<br>open fun [setRawColorBuffer](set-raw-color-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)rawColorBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)) |
| [setRawIndexBuffer](set-raw-index-buffer.md) | [androidJvm]<br>open fun [setRawIndexBuffer](set-raw-index-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)rawIndexBuffer: [IntBuffer](https://developer.android.com/reference/kotlin/java/nio/IntBuffer.html)) |
| [setRawPositionBuffer](set-raw-position-buffer.md) | [androidJvm]<br>open fun [setRawPositionBuffer](set-raw-position-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)rawPositionBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)) |
| [setRawTangentsBuffer](set-raw-tangents-buffer.md) | [androidJvm]<br>open fun [setRawTangentsBuffer](set-raw-tangents-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)rawTangentsBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)) |
| [setRawUvBuffer](set-raw-uv-buffer.md) | [androidJvm]<br>open fun [setRawUvBuffer](set-raw-uv-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)rawUvBuffer: [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html)) |
| [setTransformOffset](set-transform-offset.md) | [androidJvm]<br>open fun [setTransformOffset](set-transform-offset.md)(offset: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md)) |
| [setTransformScale](set-transform-scale.md) | [androidJvm]<br>open fun [setTransformScale](set-transform-scale.md)(scale: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [setVertexBuffer](set-vertex-buffer.md) | [androidJvm]<br>open fun [setVertexBuffer](set-vertex-buffer.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)vertexBuffer: VertexBuffer) |
