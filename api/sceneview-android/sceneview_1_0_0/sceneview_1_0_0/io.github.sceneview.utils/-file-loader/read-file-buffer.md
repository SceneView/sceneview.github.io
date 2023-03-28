//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.utils](../index.md)/[FileLoader](index.md)/[readFileBuffer](read-file-buffer.md)

# readFileBuffer

[androidJvm]\
fun [readFileBuffer](read-file-buffer.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)?

Load a file content buffer from a local source

The file location can be:

- 
   A relative asset file location *models/mymodel.glb*
- 
   An android resource from the res folder *context.getResourceUri(R.raw.mymodel)*
- 
   A File path *Uri.fromFile(myModelFile).path*
- 
   An http or https url *https://mydomain.com/mymodel.glb*