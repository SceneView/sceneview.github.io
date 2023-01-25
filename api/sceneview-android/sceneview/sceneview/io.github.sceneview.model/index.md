//[sceneview](../../index.md)/[io.github.sceneview.model](index.md)

# Package io.github.sceneview.model

## Types

| Name | Summary |
|---|---|
| [GLBLoader](-g-l-b-loader/index.md) | [androidJvm]<br>object [GLBLoader](-g-l-b-loader/index.md) |
| [GLTFLoader](-g-l-t-f-loader/index.md) | [androidJvm]<br>object [GLTFLoader](-g-l-t-f-loader/index.md) |
| [Model](index.md#1227607086%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Model](index.md#1227607086%2FClasslikes%2F-1571379623) = FilamentAsset |
| [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623) = FilamentInstance |

## Functions

| Name | Summary |
|---|---|
| [asDeferred](as-deferred.md) | [androidJvm]<br>fun &lt;[T](as-deferred.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](as-deferred.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](as-deferred.md), [B](as-deferred.md)&gt;.[asDeferred](as-deferred.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): Deferred&lt;[T](as-deferred.md)&gt;<br>It is a Job with a result. |
| [await](await.md) | [androidJvm]<br>suspend fun &lt;[T](await.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](await.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](await.md), [B](await.md)&gt;.[await](await.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [T](await.md)<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [build](build.md) | [androidJvm]<br>suspend fun &lt;[T](build.md) : [Renderable](../com.google.ar.sceneform.rendering/-renderable/index.md), [B](build.md) : [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;&gt; [Renderable.Builder](../com.google.ar.sceneform.rendering/-renderable/-builder/index.md)&lt;[T](build.md), [B](build.md)&gt;.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html))<br>This suspending function is cancellable. If the Job of the current coroutine is cancelled or completed while this suspending function is waiting, this function stops waiting for the completion stage and immediately resumes with CancellationException. This method is intended to be used with one-shot futures, so on coroutine cancellation the CompletableFuture that corresponds to this CompletionStage (see CompletionStage.toCompletableFuture) is cancelled. If cancelling the given stage is undesired, stage.asDeferred().await() should be used instead. |
| [createInstance](create-instance.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[createInstance](create-instance.md)(): FilamentInstance? |
| [destroy](destroy.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[destroy](destroy.md)()<br>fun [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623).[destroy](destroy.md)() |
| [getAnimationIndex](get-animation-index.md) | [androidJvm]<br>fun Animator.[getAnimationIndex](get-animation-index.md)(animationName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [getRenderableByName](get-renderable-by-name.md) | [androidJvm]<br>fun [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[getRenderableByName](get-renderable-by-name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Renderable](../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)?<br>fun [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623).[getRenderableByName](get-renderable-by-name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |

## Properties

| Name | Summary |
|---|---|
| [lights](lights.md) | [androidJvm]<br>val [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623).[lights](lights.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Light](../io.github.sceneview.light/index.md#1927638868%2FClasslikes%2F-1571379623)&gt; |
| [model](model.md) | [androidJvm]<br>val [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623).[model](model.md): FilamentAsset |
| [renderableNames](renderable-names.md) | [androidJvm]<br>val [Model](index.md#1227607086%2FClasslikes%2F-1571379623).[renderableNames](renderable-names.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [renderables](renderables.md) | [androidJvm]<br>val [ModelInstance](index.md#1724271641%2FClasslikes%2F-1571379623).[renderables](renderables.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Renderable](../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623)&gt; |
