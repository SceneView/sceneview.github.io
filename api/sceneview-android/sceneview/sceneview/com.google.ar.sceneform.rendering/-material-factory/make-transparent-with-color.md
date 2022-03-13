//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[MaterialFactory](index.md)/[makeTransparentWithColor](make-transparent-with-color.md)

# makeTransparentWithColor

[androidJvm]\
open fun [makeTransparentWithColor](make-transparent-with-color.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), color: [Color](../-color/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;

Creates a transparent [Material](../-material/index.md) with the [Color](../-color/index.md) passed in. The [Color](../-color/index.md) can be modified by calling [setFloat4](../-material/set-float4.md) with [MATERIAL_COLOR](-m-a-t-e-r-i-a-l_-c-o-l-o-r.md). The metallicness, roughness, and reflectance can be modified using [setFloat](../-material/set-float.md).

#### Return

material that will render the given color

## See also

androidJvm

| | |
|---|---|
| [MATERIAL_METALLIC](-m-a-t-e-r-i-a-l_-m-e-t-a-l-l-i-c.md) |  |
| [MATERIAL_ROUGHNESS](-m-a-t-e-r-i-a-l_-r-o-u-g-h-n-e-s-s.md) |  |
| [MATERIAL_REFLECTANCE](-m-a-t-e-r-i-a-l_-r-e-f-l-e-c-t-a-n-c-e.md) |  |

## Parameters

androidJvm

| | |
|---|---|
| context | a context used for loading the material resource |
| color | the color for the material to render |