//[sceneview](../../index.md)/[io.github.sceneview.model](index.md)/[await](await.md)

# await

[androidJvm]\
suspend fun &lt;[T](await.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](await.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;.[await](await.md)(): [T](await.md)

###  Awaits for loading a Renderable with the parameters of the builder without blocking a thread

This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead.

#### Return

the created directional light

## See also

androidJvm

| | |
|---|---|
| [KTXLoader.loadEnvironment](../io.github.sceneview.environment/load-environment.md) |  |
| [HDRLoader.loadEnvironment](../io.github.sceneview.environment/load-environment.md) |  |
