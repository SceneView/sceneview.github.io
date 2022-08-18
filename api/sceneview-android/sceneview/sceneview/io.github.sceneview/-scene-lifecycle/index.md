//[sceneview](../../../index.md)/[io.github.sceneview](../index.md)/[SceneLifecycle](index.md)

# SceneLifecycle

[androidJvm]\
open class [SceneLifecycle](index.md)(sceneView: [SceneView](../-scene-view/index.md)) : [DefaultLifecycle](../../io.github.sceneview.utils/-default-lifecycle/index.md)

## Functions

| Name | Summary |
|---|---|
| [addObserver](../../io.github.sceneview.utils/-default-lifecycle/add-observer.md) | [androidJvm]<br>open override fun [addObserver](../../io.github.sceneview.utils/-default-lifecycle/add-observer.md)(observer: [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)) |
| [dispatchEvent](../../io.github.sceneview.utils/-default-lifecycle/dispatch-event.md) | [androidJvm]<br>inline fun &lt;[U](../../io.github.sceneview.utils/-default-lifecycle/dispatch-event.md) : [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)&gt; [dispatchEvent](../../io.github.sceneview.utils/-default-lifecycle/dispatch-event.md)(event: [U](../../io.github.sceneview.utils/-default-lifecycle/dispatch-event.md).() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [getCurrentState](../../io.github.sceneview.utils/-default-lifecycle/index.md#-7428479%2FFunctions%2F-1571379623) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open override fun [getCurrentState](../../io.github.sceneview.utils/-default-lifecycle/index.md#-7428479%2FFunctions%2F-1571379623)(): [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html) |
| [getObserverCount](../../io.github.sceneview.utils/-default-lifecycle/index.md#1406557992%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getObserverCount](../../io.github.sceneview.utils/-default-lifecycle/index.md#1406557992%2FFunctions%2F-1571379623)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [handleLifecycleEvent](../../io.github.sceneview.utils/-default-lifecycle/index.md#1414538918%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [handleLifecycleEvent](../../io.github.sceneview.utils/-default-lifecycle/index.md#1414538918%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [Lifecycle.Event](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.Event.html)) |
| [markState](../../io.github.sceneview.utils/-default-lifecycle/index.md#-1226332025%2FFunctions%2F-1571379623) | [androidJvm]<br>@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)<br>~~open~~ ~~fun~~ [~~markState~~](../../io.github.sceneview.utils/-default-lifecycle/index.md#-1226332025%2FFunctions%2F-1571379623)~~(~~@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)~~p0~~~~:~~ [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html)~~)~~ |
| [removeObserver](../../io.github.sceneview.utils/-default-lifecycle/remove-observer.md) | [androidJvm]<br>open override fun [removeObserver](../../io.github.sceneview.utils/-default-lifecycle/remove-observer.md)(observer: [LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)) |
| [setCurrentState](../../io.github.sceneview.utils/-default-lifecycle/index.md#1517748977%2FFunctions%2F-1571379623) | [androidJvm]<br>@[MainThread](https://developer.android.com/reference/kotlin/androidx/annotation/MainThread.html)<br>open fun [setCurrentState](../../io.github.sceneview.utils/-default-lifecycle/index.md#1517748977%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [Lifecycle.State](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.State.html)) |

## Properties

| Name | Summary |
|---|---|
| [mInternalScopeRef](../../io.github.sceneview.utils/-default-lifecycle/index.md#-374396445%2FProperties%2F-1571379623) | [androidJvm]<br>@[RestrictTo](https://developer.android.com/reference/kotlin/androidx/annotation/RestrictTo.html)(value = [[RestrictTo.Scope.LIBRARY_GROUP](https://developer.android.com/reference/kotlin/androidx/annotation/RestrictTo.Scope.LIBRARY_GROUP.html)])<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>val [mInternalScopeRef](../../io.github.sceneview.utils/-default-lifecycle/index.md#-374396445%2FProperties%2F-1571379623): [AtomicReference](https://developer.android.com/reference/kotlin/java/util/concurrent/atomic/AtomicReference.html)&lt;[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; |
| [observers](../../io.github.sceneview.utils/-default-lifecycle/observers.md) | [androidJvm]<br>val [observers](../../io.github.sceneview.utils/-default-lifecycle/observers.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[LifecycleObserver](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleObserver.html)&gt; |
| [sceneView](scene-view.md) | [androidJvm]<br>open val [sceneView](scene-view.md): [SceneView](../-scene-view/index.md) |
