//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Renderable](../index.md)/[Builder](index.md)/[setSource](set-source.md)

# setSource

[androidJvm]\
open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [B](index.md)

open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [B](index.md)

open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html), enableCaching: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [B](index.md)

open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [B](index.md)

[androidJvm]\
open fun [setSource](set-source.md)(definition: [RenderableDefinition](../../-renderable-definition/index.md)): [B](index.md)

Build a [Renderable](../index.md) from a [RenderableDefinition](../../-renderable-definition/index.md).
