//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[MaterialFactory](index.md)

# MaterialFactory

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

class [MaterialFactory](index.md)

Utility class used to construct default [Material](../-material/index.md)s.

## Functions

| Name | Summary |
|---|---|
| [makeOpaqueWithColor](make-opaque-with-color.md) | [androidJvm]<br>open fun [makeOpaqueWithColor](make-opaque-with-color.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), color: [Color](../-color/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;<br>Creates an opaque [Material](../-material/index.md) with the [Color](../-color/index.md) passed in. |
| [makeOpaqueWithTexture](make-opaque-with-texture.md) | [androidJvm]<br>open fun [makeOpaqueWithTexture](make-opaque-with-texture.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), texture: [Texture](../-texture/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;<br>Creates an opaque [Material](../-material/index.md) with the [Texture](../-texture/index.md) passed in. |
| [makeTransparentWithColor](make-transparent-with-color.md) | [androidJvm]<br>open fun [makeTransparentWithColor](make-transparent-with-color.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), color: [Color](../-color/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;<br>Creates a transparent [Material](../-material/index.md) with the [Color](../-color/index.md) passed in. |
| [makeTransparentWithTexture](make-transparent-with-texture.md) | [androidJvm]<br>open fun [makeTransparentWithTexture](make-transparent-with-texture.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), texture: [Texture](../-texture/index.md)): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[Material](../-material/index.md)&gt;<br>Creates a transparent [Material](../-material/index.md) with the [Texture](../-texture/index.md) passed in. |

## Properties

| Name | Summary |
|---|---|
| [MATERIAL_COLOR](-m-a-t-e-r-i-a-l_-c-o-l-o-r.md) | [androidJvm]<br>val [MATERIAL_COLOR](-m-a-t-e-r-i-a-l_-c-o-l-o-r.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Name of material parameter for controlling the color of [makeOpaqueWithColor](make-opaque-with-color.md) and [makeTransparentWithColor](make-transparent-with-color.md) materials. |
| [MATERIAL_METALLIC](-m-a-t-e-r-i-a-l_-m-e-t-a-l-l-i-c.md) | [androidJvm]<br>val [MATERIAL_METALLIC](-m-a-t-e-r-i-a-l_-m-e-t-a-l-l-i-c.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Name of material parameter for controlling the metallic property of all [MaterialFactory](index.md) materials. |
| [MATERIAL_REFLECTANCE](-m-a-t-e-r-i-a-l_-r-e-f-l-e-c-t-a-n-c-e.md) | [androidJvm]<br>val [MATERIAL_REFLECTANCE](-m-a-t-e-r-i-a-l_-r-e-f-l-e-c-t-a-n-c-e.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Name of material parameter for controlling the reflectance property of all  materials. |
| [MATERIAL_ROUGHNESS](-m-a-t-e-r-i-a-l_-r-o-u-g-h-n-e-s-s.md) | [androidJvm]<br>val [MATERIAL_ROUGHNESS](-m-a-t-e-r-i-a-l_-r-o-u-g-h-n-e-s-s.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Name of material parameter for controlling the roughness property of all  materials. |
| [MATERIAL_TEXTURE](-m-a-t-e-r-i-a-l_-t-e-x-t-u-r-e.md) | [androidJvm]<br>val [MATERIAL_TEXTURE](-m-a-t-e-r-i-a-l_-t-e-x-t-u-r-e.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Name of material parameter for controlling the texture of [makeOpaqueWithTexture](make-opaque-with-texture.md) and [makeTransparentWithTexture](make-transparent-with-texture.md) materials. |
