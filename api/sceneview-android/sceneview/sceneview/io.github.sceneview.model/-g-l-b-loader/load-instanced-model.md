//[sceneview](../../../index.md)/[io.github.sceneview.model](../index.md)/[GLBLoader](index.md)/[loadInstancedModel](load-instanced-model.md)

# loadInstancedModel

[androidJvm]\
suspend fun [loadInstancedModel](load-instanced-model.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), glbFileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Model](../index.md#1227607086%2FClasslikes%2F-1571379623), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[ModelInstance](../index.md#1724271641%2FClasslikes%2F-1571379623)?&gt;&gt;?

Consumes the contents of a glTF 2.0 file and produces a primary asset with one or more instances.

The given instance array must be sized to the desired number of instances. If successful, this method will populate the array with secondary instances whose resources are shared with the primary asset.
