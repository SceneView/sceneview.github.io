//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[DefaultLifecycle](index.md)

# DefaultLifecycle

[androidJvm]\
open class [DefaultLifecycle](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) : [LifecycleRegistry](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleRegistry.html)

## Functions

| Name | Summary |
|---|---|
| [addObserver](add-observer.md) | [androidJvm]<br>open override fun [addObserver](add-observer.md)(observer: [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)) |
| [dispatchEvent](dispatch-event.md) | [androidJvm]<br>inline fun &lt;[U](dispatch-event.md) : [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)&gt; [dispatchEvent](dispatch-event.md)(event: [U](dispatch-event.md).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [getCurrentState](index.md#-7428479%2FFunctions%2F-1571379623) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open override fun [getCurrentState](index.md#-7428479%2FFunctions%2F-1571379623)(): [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html) |
| [getObserverCount](index.md#1406557992%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getObserverCount](index.md#1406557992%2FFunctions%2F-1571379623)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [handleLifecycleEvent](index.md#1414538918%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [handleLifecycleEvent](index.md#1414538918%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [Lifecycle.Event](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.Event.html)) |
| [markState](index.md#-1226332025%2FFunctions%2F-1571379623) | [androidJvm]<br>@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)<br>~~open~~ ~~fun~~ [~~markState~~](index.md#-1226332025%2FFunctions%2F-1571379623)~~(~~@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)~~p0~~~~:~~ [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html)~~)~~ |
| [removeObserver](remove-observer.md) | [androidJvm]<br>open override fun [removeObserver](remove-observer.md)(observer: [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)) |
| [setCurrentState](index.md#1517748977%2FFunctions%2F-1571379623) | [androidJvm]<br>@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)<br>open fun [setCurrentState](index.md#1517748977%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html)) |

## Properties

| Name | Summary |
|---|---|
| [context](context.md) | [androidJvm]<br>val [context](context.md): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) |
| [mInternalScopeRef](index.md#-374396445%2FProperties%2F-1571379623) | [androidJvm]<br>@[RestrictTo](https://developer.android.com/reference/kotlin/androidx/annotation/RestrictTo.html)(value = [[RestrictTo.Scope.LIBRARY_GROUP](https://developer.android.com/reference/kotlin/androidx/annotation/RestrictTo.Scope.LIBRARY_GROUP.html)])<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>val [mInternalScopeRef](index.md#-374396445%2FProperties%2F-1571379623): [AtomicReference](https://developer.android.com/reference/kotlin/java/util/concurrent/atomic/AtomicReference.html)&lt;[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; |
| [observers](observers.md) | [androidJvm]<br>val [observers](observers.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)&gt; |

## Inheritors

| Name |
|---|
| [SceneLifecycle](../../io.github.sceneview/-scene-lifecycle/index.md) |
