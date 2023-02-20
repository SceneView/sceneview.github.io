//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Texture](../index.md)/[Builder](index.md)/[setSource](set-source.md)

# setSource

[androidJvm]\
open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [Texture.Builder](index.md)

Allows a [Texture](../index.md) to be constructed from [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html). Construction will be asynchronous.

#### Return

[Builder](index.md) for chaining setup calls.

## Parameters

androidJvm

| | |
|---|---|
| sourceUri | Sets a remote Uri or android resource Uri. The texture will be added to the registry using the Uri A previously registered texture with the same Uri will be re-used. |
| context | Sets the [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) used to resolve sourceUri |

[androidJvm]\
open fun [setSource](set-source.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [Texture.Builder](index.md)

Allows a [Texture](../index.md) to be constructed via callable function.

#### Return

[Builder](index.md) for chaining setup calls.

## Parameters

androidJvm

| | |
|---|---|
| inputStreamCreator | Supplies an [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html) with the [Texture](../index.md) data. |

[androidJvm]\
open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Texture.Builder](index.md)

Allows a [Texture](../index.md) to be constructed from resource. Construction will be asynchronous.

#### Return

[Builder](index.md) for chaining setup calls.

## Parameters

androidJvm

| | |
|---|---|
| resource | an android resource with raw type. A previously registered texture with the same resource id will be re-used. |
| context | [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) used for resolution |

[androidJvm]\
open fun [setSource](set-source.md)(bitmap: [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html)): [Texture.Builder](index.md)

Allows a [Texture](../index.md) to be constructed from a [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html). Construction will be immediate. 

The Bitmap must meet the following conditions to be used by Sceneform: 

- 
   [getConfig](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html#getConfig--) must be [ARGB_8888](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.Config.html#ARGB_8888).
- 
   [isPremultiplied](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html#isPremultiplied--) must be true.
- The width and height must be smaller than 4096 pixels.

## Parameters

androidJvm

| | |
|---|---|
| bitmap | [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html) source of texture data |

## Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | if the bitmap isn't valid |
