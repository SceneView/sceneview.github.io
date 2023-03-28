//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.texture](index.md)

# Package io.github.sceneview.texture

## Types

| Name | Summary |
|---|---|
| [ImageTexture](-image-texture/index.md) | [androidJvm]<br>class [ImageTexture](-image-texture/index.md) |
| [TextureSampler2D](-texture-sampler2-d/index.md) | [androidJvm]<br>class [TextureSampler2D](-texture-sampler2-d/index.md) : TextureSampler |
| [TextureSamplerExternal](-texture-sampler-external/index.md) | [androidJvm]<br>class [TextureSamplerExternal](-texture-sampler-external/index.md) : TextureSampler |
| [ViewStream](-view-stream/index.md) | [androidJvm]<br>open class [ViewStream](-view-stream/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)? = null, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0) : [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html)<br>Used to render an Android view to a native open GL texture that can then be rendered by Filament. |
| [ViewTexture](-view-texture/index.md) | [androidJvm]<br>class [ViewTexture](-view-texture/index.md) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun Stream.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): Stream<br>fun Texture.Builder.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md)): Texture<br>inline fun &lt;[T](build.md) : Texture.Builder&gt; Deferred&lt;[T](build.md)&gt;.[build](build.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), crossinline onResult: (Texture) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Job |
| [destroyStream](destroy-stream.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyStream](destroy-stream.md)(stream: Stream) |
| [destroyTexture](destroy-texture.md) | [androidJvm]<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyTexture](destroy-texture.md)(texture: Texture) |
| [destroyViewStream](destroy-view-stream.md) | [androidJvm]<br>fun Engine.[destroyViewStream](destroy-view-stream.md)(viewStream: [ViewStream](-view-stream/index.md))<br>fun [SceneView](../io.github.sceneview/-scene-view/index.md).[destroyViewStream](destroy-view-stream.md)(viewStream: [ViewStream](-view-stream/index.md)) |
| [setViewStream](set-view-stream.md) | [androidJvm]<br>fun Texture.[setViewStream](set-view-stream.md)(engine: Engine, viewStream: [ViewStream](-view-stream/index.md))<br>fun Texture.[setViewStream](set-view-stream.md)(sceneView: [SceneView](../io.github.sceneview/-scene-view/index.md), viewStream: [ViewStream](-view-stream/index.md)) |
