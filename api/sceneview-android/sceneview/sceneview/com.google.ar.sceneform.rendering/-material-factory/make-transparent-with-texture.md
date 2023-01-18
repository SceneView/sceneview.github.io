//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[MaterialFactory](index.md)/[makeTransparentWithTexture](make-transparent-with-texture.md)

# makeTransparentWithTexture

[androidJvm]\
open fun [makeTransparentWithTexture](make-transparent-with-texture.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), texture: [Texture](../-texture/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;

Creates a transparent [Material](../-material/index.md) with the [Texture](../-texture/index.md) passed in. The [Texture](../-texture/index.md) can be modified by calling [setTexture](../-material/set-texture.md) with [MATERIAL_TEXTURE](-m-a-t-e-r-i-a-l_-t-e-x-t-u-r-e.md). The metallicness, roughness, and reflectance can be modified using [setFloat](../-material/set-float.md).

#### Return

material that will render the given texture

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
| texture | the texture for the material to render |
