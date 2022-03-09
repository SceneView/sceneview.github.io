//[arsceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ArResourceManager](index.md)

# ArResourceManager

[androidJvm]\
open class [ArResourceManager](index.md)

Minimal resource manager. Maintains mappings from ids to created resources and a task executor dedicated to loading resources asynchronously.

## Functions

| Name | Summary |
|---|---|
| [addResourceHolder](add-resource-holder.md) | [androidJvm]<br>open fun [addResourceHolder](add-resource-holder.md)(resource: [ResourceHolder](../../../../sceneview/sceneview/com.google.ar.sceneform.resources/-resource-holder/index.md)) |
| [destroyAllResources](destroy-all-resources.md) | [androidJvm]<br>open fun [destroyAllResources](destroy-all-resources.md)()<br>Forcibly deletes all tracked references |
| [reclaimReleasedResources](reclaim-released-resources.md) | [androidJvm]<br>open fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

## Properties

| Name | Summary |
|---|---|
| [depthTextureCleanupRegistry](depth-texture-cleanup-registry.md) | [androidJvm]<br>private val [depthTextureCleanupRegistry](depth-texture-cleanup-registry.md): [CleanupRegistry](../../../../arsceneview/com.google.ar.sceneform.rendering/-cleanup-registry/index.md)&lt;[DepthTexture](../-depth-texture/index.md)&gt; |
| [instance](instance.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open val [instance](instance.md): [ArResourceManager](index.md) |
