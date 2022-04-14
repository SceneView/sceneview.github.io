//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CleanupRegistry](index.md)

# CleanupRegistry

[androidJvm]\
open class [CleanupRegistry](index.md)&lt;[T](index.md)&gt; : [ResourceHolder](../../com.google.ar.sceneform.resources/-resource-holder/index.md)

Maintains a [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html) and executes a [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html) after each object in the queue is garbage collected.

## Constructors

| | |
|---|---|
| [CleanupRegistry](-cleanup-registry.md) | [androidJvm]<br>open fun [CleanupRegistry](-cleanup-registry.md)() |
| [CleanupRegistry](-cleanup-registry.md) | [androidJvm]<br>open fun [CleanupRegistry](-cleanup-registry.md)(cleanupItemHashSet: [HashSet](https://developer.android.com/reference/kotlin/java/util/HashSet.html)&lt;[CleanupItem](../-cleanup-item/index.md)&lt;[T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)&gt;&gt;, referenceQueue: [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html)&lt;[T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)&gt;) |

## Functions

| Name | Summary |
|---|---|
| [destroyAllResources](destroy-all-resources.md) | [androidJvm]<br>open fun [destroyAllResources](destroy-all-resources.md)()<br>Ignores reference count and releases any associated resources |
| [reclaimReleasedResources](reclaim-released-resources.md) | [androidJvm]<br>open fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Polls the [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html) for garbage collected objects and runs the associated |
| [register](register.md) | [androidJvm]<br>open fun [register](register.md)(trackedObject: [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md), cleanupCallback: [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html))<br>Adds trackedOBject to the [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html). |
