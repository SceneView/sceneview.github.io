//[sceneview_1_0_0](../../../../index.md)/[io.github.sceneview.texture](../../index.md)/[ImageTexture](../index.md)/[Builder](index.md)

# Builder

[androidJvm]\
class [Builder](index.md) : Texture.Builder

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [androidJvm]<br>fun [Builder](-builder.md)() |

## Functions

| Name | Summary |
|---|---|
| [bitmap](bitmap.md) | [androidJvm]<br>fun [bitmap](bitmap.md)(bitmap: [Bitmap](https://developer.android.com/reference/kotlin/android/graphics/Bitmap.html), type: TextureType = TextureType.COLOR): [ImageTexture.Builder](index.md) |
| [build](build.md) | [androidJvm]<br>open override fun [build](build.md)(engine: Engine): Texture |
| [depth](../../-view-texture/-builder/index.md#1313264849%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [depth](../../-view-texture/-builder/index.md#1313264849%2FFunctions%2F-602047187)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 1)p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Texture.Builder |
| [format](../../-view-texture/-builder/index.md#1571567029%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [format](../../-view-texture/-builder/index.md#1571567029%2FFunctions%2F-602047187)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: Texture.InternalFormat): Texture.Builder |
| [height](../../-view-texture/-builder/index.md#-1567470501%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [height](../../-view-texture/-builder/index.md#-1567470501%2FFunctions%2F-602047187)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 1)p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Texture.Builder |
| [image](image.md) | [androidJvm]<br>fun [image](image.md)(assets: [AssetManager](https://developer.android.com/reference/kotlin/android/content/res/AssetManager.html), fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: TextureType = TextureType.COLOR): [ImageTexture.Builder](index.md)<br>fun [image](image.md)(resources: [Resources](https://developer.android.com/reference/kotlin/android/content/res/Resources.html), resourceId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: TextureType = TextureType.COLOR): [ImageTexture.Builder](index.md) |
| [importTexture](../../-view-texture/-builder/index.md#-379671335%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [importTexture](../../-view-texture/-builder/index.md#-379671335%2FFunctions%2F-602047187)(p0: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): Texture.Builder |
| [levels](../../-view-texture/-builder/index.md#567960339%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [levels](../../-view-texture/-builder/index.md#567960339%2FFunctions%2F-602047187)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 1)p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Texture.Builder |
| [sampler](../../-view-texture/-builder/index.md#1641360720%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [sampler](../../-view-texture/-builder/index.md#1641360720%2FFunctions%2F-602047187)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: Texture.Sampler): Texture.Builder |
| [swizzle](../../-view-texture/-builder/index.md#-558095253%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [swizzle](../../-view-texture/-builder/index.md#-558095253%2FFunctions%2F-602047187)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: Texture.Swizzle, @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p1: Texture.Swizzle, @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p2: Texture.Swizzle, @[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p3: Texture.Swizzle): Texture.Builder |
| [usage](../../-view-texture/-builder/index.md#87475507%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [usage](../../-view-texture/-builder/index.md#87475507%2FFunctions%2F-602047187)(p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Texture.Builder |
| [width](../../-view-texture/-builder/index.md#1503935214%2FFunctions%2F-602047187) | [androidJvm]<br>@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)<br>open fun [width](../../-view-texture/-builder/index.md#1503935214%2FFunctions%2F-602047187)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 1)p0: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Texture.Builder |
