//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[LoadHelper](index.md)/[fromUri](from-uri.md)

# fromUri

[androidJvm]\
open fun [fromUri](from-uri.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;

Creates different InputStreams depending on the contents of the Uri

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | for Uri's that can't be loaded. |

[androidJvm]\
open fun [fromUri](from-uri.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)requestProperty: [Map](https://developer.android.com/reference/kotlin/java/util/Map.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)&gt;): [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;

Creates different InputStreams depending on the contents of the Uri.

## Parameters

androidJvm

| | |
|---|---|
| requestProperty | Adds connection properties to created input stream. |

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | for Uri's that can't be loaded. |
