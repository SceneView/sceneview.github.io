//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Material](../index.md)/[Builder](index.md)/[setSource](set-source.md)

# setSource

[androidJvm]\
open fun [setSource](set-source.md)(materialBuffer: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Material.Builder](index.md)

Allows a [Material](../index.md) to be created with data. 

Construction will be immediate. Please use [setRegistryId](../../../../../arsceneview/com.google.ar.sceneform.rendering/-material/-builder/set-registry-id.md) to register this material for reuse.

#### Return

[Builder](index.md) for chaining setup calls

## Parameters

androidJvm

| | |
|---|---|
| materialBuffer | Sets the material data. |

[androidJvm]\
open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [Material.Builder](index.md)

Allows a [Material](../index.md) to be constructed from [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html). Construction will be asynchronous.

#### Return

[Builder](index.md) for chaining setup calls

## Parameters

androidJvm

| | |
|---|---|
| context | Sets the [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) used for loading the resource |
| sourceUri | Sets a remote Uri or android resource Uri. The material will be added to the registry using the Uri. A previously registered material with the same Uri will be re-used. |

[androidJvm]\
open fun [setSource](set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Material.Builder](index.md)

Allows a [Material](../index.md) to be constructed from resource. 

Construction will be asynchronous.

#### Return

[Builder](index.md) for chaining setup calls

## Parameters

androidJvm

| | |
|---|---|
| context | Sets the [Context](https://developer.android.com/reference/kotlin/android/content/Context.html) used for loading the resource |
| resource | an android resource with raw type. A previously registered material with the same resource id will be re-used. |

[androidJvm]\
open fun [setSource](set-source.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [Material.Builder](index.md)

Allows a [Material](../index.md) to be constructed via callable function.

#### Return

[Builder](index.md) for chaining setup calls

## Parameters

androidJvm

| | |
|---|---|
| inputStreamCreator | Supplies an [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html) with the [Material](../index.md) data |
