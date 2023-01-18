//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[LoadGltfListener](index.md)

# LoadGltfListener

[androidJvm]\
interface [LoadGltfListener](index.md)

Interface callbacks for events that occur when loading a gltf file into a renderable.

## Types

| Name | Summary |
|---|---|
| [GltfLoadStage](-gltf-load-stage/index.md) | [androidJvm]<br>enum [GltfLoadStage](-gltf-load-stage/index.md)<br>Defines the current stage of the load operation, each value supersedes the previous. |

## Functions

| Name | Summary |
|---|---|
| [onFinishedFetchingMaterials](on-finished-fetching-materials.md) | [androidJvm]<br>abstract fun [onFinishedFetchingMaterials](on-finished-fetching-materials.md)() |
| [onFinishedLoadingModel](on-finished-loading-model.md) | [androidJvm]<br>abstract fun [onFinishedLoadingModel](on-finished-loading-model.md)(durationMs: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [onFinishedReadingFiles](on-finished-reading-files.md) | [androidJvm]<br>abstract fun [onFinishedReadingFiles](on-finished-reading-files.md)(durationMs: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [onReadingFilesFailed](on-reading-files-failed.md) | [androidJvm]<br>abstract fun [onReadingFilesFailed](on-reading-files-failed.md)(exception: [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html)) |
| [reportBytesDownloaded](report-bytes-downloaded.md) | [androidJvm]<br>abstract fun [reportBytesDownloaded](report-bytes-downloaded.md)(bytes: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [setLoadingStage](set-loading-stage.md) | [androidJvm]<br>abstract fun [setLoadingStage](set-loading-stage.md)(stage: [LoadGltfListener.GltfLoadStage](-gltf-load-stage/index.md)) |
| [setModelSize](set-model-size.md) | [androidJvm]<br>abstract fun [setModelSize](set-model-size.md)(modelSizeMeters: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
