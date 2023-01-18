//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[SceneformBufferUtils](index.md)

# SceneformBufferUtils

[androidJvm]\
class [SceneformBufferUtils](index.md)

A simple class to read InputStreams Once the data is read it can be accessed as a ByteBuffer.

## Functions

| Name | Summary |
|---|---|
| [copyByteBuffer](copy-byte-buffer.md) | [androidJvm]<br>open fun [copyByteBuffer](copy-byte-buffer.md)(in: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [copyByteBufferToArray](copy-byte-buffer-to-array.md) | [androidJvm]<br>open fun [copyByteBufferToArray](copy-byte-buffer-to-array.md)(in: [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [inputStreamCallableToByteArray](input-stream-callable-to-byte-array.md) | [androidJvm]<br>open fun [inputStreamCallableToByteArray](input-stream-callable-to-byte-array.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [inputStreamToByteArray](input-stream-to-byte-array.md) | [androidJvm]<br>open fun [inputStreamToByteArray](input-stream-to-byte-array.md)(input: [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [inputStreamToByteBuffer](input-stream-to-byte-buffer.md) | [androidJvm]<br>open fun [inputStreamToByteBuffer](input-stream-to-byte-buffer.md)(inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [readFile](read-file.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [readFile](read-file.md)(assets: [AssetManager](https://developer.android.com/reference/kotlin/android/content/res/AssetManager.html), path: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [readStream](read-stream.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>open fun [readStream](read-stream.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)inputStream: [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
