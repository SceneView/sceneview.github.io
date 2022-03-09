//[sceneview](../../../index.md)/[io.github.sceneview.utils](../index.md)/[ResourceLoader](index.md)/[fileBuffer](file-buffer.md)

# fileBuffer

[androidJvm]\

@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)

suspend fun [fileBuffer](file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?

###  Load a file content buffer from different sources

The file location can be:

- 
   A relative asset file location *models/mymodel.glb*
- 
   An android resource from the res folder *context.getResourceUri(R.raw.mymodel)*
- 
   A File path *Uri.fromFile(myModelFile).path*
- 
   An http or https url *https://mydomain.com/mymodel.glb*

## See also

androidJvm

| | |
|---|---|
| okHttpClient |  |
