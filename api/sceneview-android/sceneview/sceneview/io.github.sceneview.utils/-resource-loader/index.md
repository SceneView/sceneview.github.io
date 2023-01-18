//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[ResourceLoader](index.md)

# ResourceLoader

[androidJvm]\
object [ResourceLoader](index.md)

## Functions

| Name | Summary |
|---|---|
| [fileBuffer](file-buffer.md) | [androidJvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>suspend fun [fileBuffer](file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?<br>The file location can be: |
| [localFileBuffer](local-file-buffer.md) | [androidJvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>fun [localFileBuffer](local-file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?<br>The file location can be: |
| [useFileBuffer](use-file-buffer.md) | [androidJvm]<br>suspend fun &lt;[R](use-file-buffer.md)&gt; [useFileBuffer](use-file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), block: suspend ([ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?) -&gt; [R](use-file-buffer.md)): [R](use-file-buffer.md) |
| [useFileBufferNotNull](use-file-buffer-not-null.md) | [androidJvm]<br>suspend fun &lt;[R](use-file-buffer-not-null.md)&gt; [useFileBufferNotNull](use-file-buffer-not-null.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), block: suspend ([ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) -&gt; [R](use-file-buffer-not-null.md)): [R](use-file-buffer-not-null.md)? |
| [useLocalFileBuffer](use-local-file-buffer.md) | [androidJvm]<br>fun &lt;[R](use-local-file-buffer.md)&gt; [useLocalFileBuffer](use-local-file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), block: ([ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?) -&gt; [R](use-local-file-buffer.md)): [R](use-local-file-buffer.md) |
| [useLocalFileBufferNotNull](use-local-file-buffer-not-null.md) | [androidJvm]<br>fun &lt;[R](use-local-file-buffer-not-null.md)&gt; [useLocalFileBufferNotNull](use-local-file-buffer-not-null.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), block: ([ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)) -&gt; [R](use-local-file-buffer-not-null.md)): [R](use-local-file-buffer-not-null.md)? |

## Properties

| Name | Summary |
|---|---|
| [fuelManager](fuel-manager.md) | [androidJvm]<br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)<br>var [fuelManager](fuel-manager.md): FuelManager<br>configuration. |
