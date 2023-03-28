//[sceneview_1_0_0](../../index.md)/[io.github.sceneview.utils](index.md)

# Package io.github.sceneview.utils

## Types

| Name | Summary |
|---|---|
| [Color](index.md#289679020%2FClasslikes%2F-602047187) | [androidJvm]<br>typealias [Color](index.md#289679020%2FClasslikes%2F-602047187) = [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |
| [FileLoader](-file-loader/index.md) | [androidJvm]<br>object [FileLoader](-file-loader/index.md) |
| [FrameTime](-frame-time/index.md) | [androidJvm]<br>data class [FrameTime](-frame-time/index.md)(val nanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), val lastNanoseconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null)<br>Provides time information for the current frame |
| [IBLPrefilter](-i-b-l-prefilter/index.md) | [androidJvm]<br>class [IBLPrefilter](-i-b-l-prefilter/index.md)(engine: Engine)<br>IBLPrefilter creates and initializes GPU state common to all environment map filters |
| [SurfaceMirorer](-surface-mirorer/index.md) | [androidJvm]<br>class [SurfaceMirorer](-surface-mirorer/index.md)(engine: Engine, view: View, renderer: Renderer) |

## Functions

| Name | Summary |
|---|---|
| [clone](clone.md) | [androidJvm]<br>fun [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html).[clone](clone.md)(): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)<br>fun [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html).[clone](clone.md)(): [FloatBuffer](https://developer.android.com/reference/kotlin/java/nio/FloatBuffer.html) |
| [Color](-color.md) | [androidJvm]<br>fun [Color](-color.md)(drawable: [ColorDrawable](https://developer.android.com/reference/kotlin/android/graphics/drawable/ColorDrawable.html)): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)<br>fun [Color](-color.md)(color: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |
| [colorOf](color-of.md) | [androidJvm]<br>fun [colorOf](color-of.md)(color: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)<br>fun [colorOf](color-of.md)(rgb: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)<br>fun [colorOf](color-of.md)(r: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, g: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, b: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f, a: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 1.0f): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |
| [doOnApplyWindowInsets](do-on-apply-window-insets.md) | [androidJvm]<br>fun [View](https://developer.android.com/reference/kotlin/android/view/View.html).[doOnApplyWindowInsets](do-on-apply-window-insets.md)(action: (systemBarsInsets: [Insets](https://developer.android.com/reference/kotlin/androidx/core/graphics/Insets.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [getResourceUri](get-resource-uri.md) | [androidJvm]<br>fun [Context](https://developer.android.com/reference/kotlin/android/content/Context.html).[getResourceUri](get-resource-uri.md)(resId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Retrieve a android resource uri from a res id |
| [loadFileBuffer](load-file-buffer.md) | [androidJvm]<br>suspend fun [Context](https://developer.android.com/reference/kotlin/android/content/Context.html).[loadFileBuffer](load-file-buffer.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html)? |
| [readFileBuffer](read-file-buffer.md) | [androidJvm]<br>fun [AssetManager](https://developer.android.com/reference/kotlin/android/content/res/AssetManager.html).[readFileBuffer](read-file-buffer.md)(fileLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ByteBuffer](https://developer.android.com/reference/kotlin/java/nio/ByteBuffer.html) |
| [setFullScreen](set-full-screen.md) | [androidJvm]<br>fun [View](https://developer.android.com/reference/kotlin/android/view/View.html).[setFullScreen](set-full-screen.md)(fullScreen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, hideSystemBars: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, fitsSystemWindows: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true)<br>fun [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html).[setFullScreen](set-full-screen.md)(rootView: [View](https://developer.android.com/reference/kotlin/android/view/View.html), fullScreen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, hideSystemBars: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, fitsSystemWindows: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true)<br>[androidJvm]<br>fun [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html).[setFullScreen](set-full-screen.md)(fullScreen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, hideSystemBars: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, fitsSystemWindows: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true)<br>Sets the Android FitsSystemWindows and WindowInsetsController properties. |
| [setKeepScreenOn](set-keep-screen-on.md) | [androidJvm]<br>fun [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html).[setKeepScreenOn](set-keep-screen-on.md)(keepScreenOn: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true) |
| [toByteArray](to-byte-array.md) | [androidJvm]<br>fun [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html).[toByteArray](to-byte-array.md)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [toColor](to-color.md) | [androidJvm]<br>fun [FloatArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float-array/index.html).[toColor](to-color.md)(): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md) |
| [toLinearSpace](to-linear-space.md) | [androidJvm]<br>fun [Color](index.md#289679020%2FClasslikes%2F-602047187).[toLinearSpace](to-linear-space.md)(): [Float4](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float4/index.md)<br>If rendering in linear space, first convert the gray scaled values to linear space by rising to the power 2.2 |