//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CleanupRegistry](index.md)/[reclaimReleasedResources](reclaim-released-resources.md)

# reclaimReleasedResources

[androidJvm]\
open fun [reclaimReleasedResources](reclaim-released-resources.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)

Polls the [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html) for garbage collected objects and runs the associated 

#### Return

count of resources remaining.
