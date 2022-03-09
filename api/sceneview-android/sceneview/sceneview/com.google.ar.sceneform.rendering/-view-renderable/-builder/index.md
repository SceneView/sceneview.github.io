//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[ViewRenderable](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md) : [Renderable.Builder](../../-renderable/-builder/index.md)&lt;[ViewRenderable](../index.md), [ViewRenderable.Builder](index.md)&gt; 

Factory class for [ViewRenderable](../index.md)

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>open fun [build](build.md)(): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[ViewRenderable](../index.md)&gt;<br>Constructs a [Renderable](../../-renderable/index.md) with the parameters of the builder. |
| [hasSource](../../-renderable/-builder/has-source.md) | [androidJvm]<br>open fun [hasSource](../../-renderable/-builder/has-source.md)(): [Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)<br>True if a source function will be called during build |
| [setAnimationFrameRate](index.md#131776741%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setAnimationFrameRate](index.md#131776741%2FFunctions%2F-1571379623)(frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [B](../../-renderable/-builder/index.md)<br>Sets the number of frames per seconds defined in the asset. |
| [setAsyncLoadEnabled](index.md#788549410%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setAsyncLoadEnabled](index.md#788549410%2FFunctions%2F-1571379623)(asyncLoadEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [B](../../-renderable/-builder/index.md)<br>Enable textures async loading after first rendering. |
| [setIsFilamentGltf](../../-renderable/-builder/set-is-filament-gltf.md) | [androidJvm]<br>open fun [setIsFilamentGltf](../../-renderable/-builder/set-is-filament-gltf.md)(isFilamentGltf: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [B](../../-renderable/-builder/index.md) |
| [setRegistryId](index.md#-1608346164%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setRegistryId](index.md#-1608346164%2FFunctions%2F-1571379623)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)registryId: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [B](../../-renderable/-builder/index.md) |
| [setSizer](set-sizer.md) | [androidJvm]<br>open fun [setSizer](set-sizer.md)(viewSizer: [ViewSizer](../../-view-sizer/index.md)): [ViewRenderable.Builder](index.md)<br>Set the [ViewSizer](../../-view-sizer/index.md) that controls the size of the built [ViewRenderable](../index.md) in the [SceneView](../../../io.github.sceneview/-scene-view/index.md). |
| [setSource](../../-renderable/-builder/set-source.md) | [androidJvm]<br>open fun [setSource](../../-renderable/-builder/set-source.md)(definition: [RenderableDefinition](../../-renderable-definition/index.md)): [B](../../-renderable/-builder/index.md)<br>Build a [Renderable](../../-renderable/index.md) from a [RenderableDefinition](../../-renderable-definition/index.md).<br>[androidJvm]<br>open fun [setSource](../../-renderable/-builder/set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)): [B](../../-renderable/-builder/index.md)<br>open fun [setSource](../../-renderable/-builder/set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), resource: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [B](../../-renderable/-builder/index.md)<br>open fun [setSource](../../-renderable/-builder/set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), inputStreamCreator: [Callable](https://developer.android.com/reference/kotlin/java/util/concurrent/Callable.html)&lt;[InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)&gt;): [B](../../-renderable/-builder/index.md)<br>open fun [setSource](../../-renderable/-builder/set-source.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sourceUri: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html), enableCaching: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [B](../../-renderable/-builder/index.md) |

## Properties

| Name | Summary |
|---|---|
| [horizontalAlignment](horizontal-alignment.md) | [androidJvm]<br>private open var [horizontalAlignment](horizontal-alignment.md): [ViewRenderable.HorizontalAlignment](../-horizontal-alignment/index.md) |
| [verticalAlignment](vertical-alignment.md) | [androidJvm]<br>private open var [verticalAlignment](vertical-alignment.md): [ViewRenderable.VerticalAlignment](../-vertical-alignment/index.md) |
| [view](view.md) | [androidJvm]<br>@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)<br>private open var [view](view.md): [View](https://developer.android.com/reference/kotlin/android/view/View.html) |
