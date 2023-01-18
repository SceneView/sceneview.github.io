//[sceneview](../../../index.md)/[com.google.ar.sceneform.resources](../index.md)/[ResourceHolder](index.md)

# ResourceHolder

[androidJvm]\
interface [ResourceHolder](index.md)

Pool or cachce for resources

## Functions

| Name | Summary |
|---|---|
| [destroyAllResources](destroy-all-resources.md) | [androidJvm]<br>abstract fun [destroyAllResources](destroy-all-resources.md)()<br>Ignores reference count and disposes any associated resources. |
| [reclaimReleasedResources](reclaim-released-resources.md) | [androidJvm]<br>abstract fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Polls for garbage collected objects and disposes associated data. |

## Inheritors

| Name |
|---|
| [ResourceRegistry](../-resource-registry/index.md) |
