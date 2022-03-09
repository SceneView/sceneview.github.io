//[sceneview](../../index.md)/[io.github.sceneview.model](index.md)

# Package io.github.sceneview.model

## Types

| Name | Summary |
|---|---|
| [GLBLoader](-g-l-b-loader/index.md) | [androidJvm]<br>object [GLBLoader](-g-l-b-loader/index.md) |

## Functions

| Name | Summary |
|---|---|
| [asDeferred](as-deferred.md) | [androidJvm]<br>fun &lt;[T](as-deferred.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](as-deferred.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;.[asDeferred](as-deferred.md)(): Deferred&lt;[T](as-deferred.md)&gt;<br>It is a Job with a result. |
| [await](await.md) | [androidJvm]<br>suspend fun &lt;[T](await.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](await.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;.[await](await.md)(): [T](await.md)<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [build](build.md) | [androidJvm]<br>suspend fun &lt;[T](build.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](build.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;.[build](build.md)(coroutineScope: [LifecycleCoroutineScope](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleCoroutineScope.html))<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
