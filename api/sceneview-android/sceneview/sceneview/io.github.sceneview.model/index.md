//[sceneview](../../index.md)/[io.github.sceneview.model](index.md)

# Package io.github.sceneview.model

## Types

| Name | Summary |
|---|---|
| [GLBLoader](-g-l-b-loader/index.md) | [androidJvm]<br>object [GLBLoader](-g-l-b-loader/index.md) |
| [Model](index.md#1227607086%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Model](index.md#1227607086%2FClasslikes%2F-1571379623) = FilamentAsset |

## Functions

| Name | Summary |
|---|---|
| [animationDuration](animation-duration.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[animationDuration](animation-duration.md)(animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [animationName](animation-name.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[animationName](animation-name.md)(animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [applyAnimation](apply-animation.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[applyAnimation](apply-animation.md)(animationIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), time: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [asDeferred](as-deferred.md) | [androidJvm]<br>fun &lt;[T](as-deferred.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](as-deferred.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;.[asDeferred](as-deferred.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): Deferred&lt;[T](as-deferred.md)&gt;<br>It is a Job with a result. |
| [await](await.md) | [androidJvm]<br>suspend fun &lt;[T](await.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](await.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;.[await](await.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [T](await.md)<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [build](build.md) | [androidJvm]<br>suspend fun &lt;[T](build.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](build.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html))<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [destroy](destroy.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[destroy](destroy.md)() |

## Properties

| Name | Summary |
|---|---|
| [allEntities](all-entities.md) | [androidJvm]<br>val [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[allEntities](all-entities.md): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [animationCount](animation-count.md) | [androidJvm]<br>val [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[animationCount](animation-count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [animationDuration](animation-duration.md) | [androidJvm]<br>val [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[animationDuration](animation-duration.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [animationName](animation-name.md) | [androidJvm]<br>val [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[animationName](animation-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
