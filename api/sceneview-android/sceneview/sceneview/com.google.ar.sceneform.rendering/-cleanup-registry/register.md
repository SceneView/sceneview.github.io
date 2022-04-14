//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CleanupRegistry](index.md)/[register](register.md)

# register

[androidJvm]\
open fun [register](register.md)(trackedObject: [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md), cleanupCallback: [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html))

Adds trackedOBject to the [ReferenceQueue](https://developer.android.com/reference/kotlin/java/lang/ref/ReferenceQueue.html).

## Parameters

androidJvm

| | |
|---|---|
| trackedObject | The target to be tracked. |
| cleanupCallback | Will be called after trackedOBject is disposed. |
