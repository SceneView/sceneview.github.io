//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[CleanupItem](index.md)

# CleanupItem

[androidJvm]\
open class [CleanupItem](index.md)&lt;[T](index.md)&gt; : [PhantomReference](https://developer.android.com/reference/kotlin/java/lang/ref/PhantomReference.html)&lt;[T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md)&gt; 

Runs a [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html) when a registered object is destroyed. 

For each object of type T registered, a [CleanupItem](index.md) will be created. The registered object's lifecycle will be tracked and when it is disposed the given [Runnable](https://developer.android.com/reference/kotlin/java/lang/Runnable.html) will be run.

## Functions

| Name | Summary |
|---|---|
| [clear](index.md#1185955492%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [clear](index.md#1185955492%2FFunctions%2F-1571379623)() |
| [enqueue](index.md#-1582683575%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [enqueue](index.md#-1582683575%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.md#1298606984%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [get](index.md#1298606984%2FFunctions%2F-1571379623)(): [T](../../com.google.ar.sceneform.collision/-collision-system/raycast-all.md) |
| [isEnqueued](index.md#1222417347%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [isEnqueued](index.md#1222417347%2FFunctions%2F-1571379623)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reachabilityFence](index.md#617960068%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [reachabilityFence](index.md#617960068%2FFunctions%2F-1571379623)(ref: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
