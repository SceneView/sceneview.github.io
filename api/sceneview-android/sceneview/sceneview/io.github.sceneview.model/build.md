//[sceneview](../../index.md)/[io.github.sceneview.model](index.md)/[build](build.md)

# build

[androidJvm]\
suspend fun &lt;[T](build.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](build.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;.[build](build.md)(coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html))

###  Load a Renderable in a coroutine scope without blocking a thread

This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead.

#### Return

the created directional light

## See also

androidJvm

| | |
|---|---|
| [KTXLoader.loadEnvironment](../io.github.sceneview.environment/load-environment.md) |  |
| [HDRLoader.loadEnvironment](../io.github.sceneview.environment/load-environment.md) |  |
