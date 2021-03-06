//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Renderable](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
abstract class [Builder](index.md)&lt;[T](index.md) : [Renderable](../index.md)?, [B](index.md) : [Renderable.Builder](index.md)&lt;[T](../../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md), [B](index.md)&gt;?&gt;

Used to programmatically construct a [Renderable](../index.md). Builder data is stored, not copied. Be careful when modifying the data before or between build calls.

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[T](../../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt;<br>Constructs a [Renderable](../index.md) with the parameters of the builder. |
| [hasSource](has-source.md) | [androidJvm]<br>open fun [hasSource](has-source.md)(): [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)<br>True if a source function will be called during build |
| [setIsFilamentGltf](set-is-filament-gltf.md) | [androidJvm]<br>open fun [setIsFilamentGltf](set-is-filament-gltf.md)(isFilamentGltf: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [B](index.md) |
| [setSource](set-source.md) | [androidJvm]<br>open fun [setSource](set-source.md)(definition: [RenderableDefinition](../../-renderable-definition/index.md)): [B](index.md)<br>Build a [Renderable](../index.md) from a [RenderableDefinition](../../-renderable-definition/index.md).<br>[androidJvm]<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [B](index.md)<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [B](index.md)<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [B](index.md)<br>open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html), uriResolver: ([String](https://developer.android.com/reference/kotlin/java/lang/String.html)) -&gt; [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [B](index.md) |

## Properties

| Name | Summary |
|---|---|
| [animationFrameRate](animation-frame-rate.md) | [androidJvm]<br>private open var [animationFrameRate](animation-frame-rate.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [asyncLoadEnabled](async-load-enabled.md) | [androidJvm]<br>private open var [asyncLoadEnabled](async-load-enabled.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [registryId](registry-id.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>protected open var [registryId](registry-id.md): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |

## Inheritors

| Name |
|---|
| [Builder](../../-view-renderable/-builder/index.md) |
| [Builder](../../-model-renderable/-builder/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [asDeferred](../../../io.github.sceneview.model/as-deferred.md) | [androidJvm]<br>fun &lt;[T](../../../io.github.sceneview.model/as-deferred.md) : [Renderable](../index.md), [B](../../../io.github.sceneview.model/as-deferred.md) : [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/as-deferred.md), [B](../../../io.github.sceneview.model/as-deferred.md)&gt;&gt; [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/as-deferred.md), [B](../../../io.github.sceneview.model/as-deferred.md)&gt;.[asDeferred](../../../io.github.sceneview.model/as-deferred.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): Deferred&lt;[T](../../../io.github.sceneview.model/as-deferred.md)&gt;<br>It is a Job with a result. |
| [await](../../../io.github.sceneview.model/await.md) | [androidJvm]<br>suspend fun &lt;[T](../../../io.github.sceneview.model/await.md) : [Renderable](../index.md), [B](../../../io.github.sceneview.model/await.md) : [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/await.md), [B](../../../io.github.sceneview.model/await.md)&gt;&gt; [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/await.md), [B](../../../io.github.sceneview.model/await.md)&gt;.[await](../../../io.github.sceneview.model/await.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [T](../../../io.github.sceneview.model/await.md)<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [build](../../../io.github.sceneview.model/build.md) | [androidJvm]<br>suspend fun &lt;[T](../../../io.github.sceneview.model/build.md) : [Renderable](../index.md), [B](../../../io.github.sceneview.model/build.md) : [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/build.md), [B](../../../io.github.sceneview.model/build.md)&gt;&gt; [Renderable.Builder](index.md)&lt;[T](../../../io.github.sceneview.model/build.md), [B](../../../io.github.sceneview.model/build.md)&gt;.[build](../../../io.github.sceneview.model/build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html))<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
