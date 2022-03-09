//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[LoadHelper](index.md)/[fromResource](from-resource.md)

# fromResource

[androidJvm]\
open fun [fromResource](from-resource.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;

Creates an InputStream from an Android resource ID.

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | for resources that can't be loaded. |
