//[sceneview](../../index.md)/[io.github.sceneview.renderable](index.md)

# Package io.github.sceneview.renderable

## Types

| Name | Summary |
|---|---|
| [Renderable](index.md#286838466%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [Renderable](index.md#286838466%2FClasslikes%2F-1571379623) = [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [RenderableInstance](index.md#841054893%2FClasslikes%2F-1571379623) | [androidJvm]<br>typealias [RenderableInstance](index.md#841054893%2FClasslikes%2F-1571379623) = [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Functions

| Name | Summary |
|---|---|
| [build](build.md) | [androidJvm]<br>fun IndexBuffer.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): IndexBuffer<br>fun RenderableManager.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)): [Renderable](index.md#286838466%2FClasslikes%2F-1571379623)<br>fun VertexBuffer.Builder.[build](build.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html)? = null): VertexBuffer |
| [destroy](destroy.md) | [androidJvm]<br>fun IndexBuffer.[destroy](destroy.md)()<br>fun VertexBuffer.[destroy](destroy.md)() |
| [getMaterial](get-material.md) | [androidJvm]<br>fun [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[getMaterial](get-material.md)(): MaterialInstance |
| [getMaterialAt](get-material-at.md) | [androidJvm]<br>fun [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[getMaterialAt](get-material-at.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)primitiveIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): MaterialInstance |
| [setBuffer](set-buffer.md) | [androidJvm]<br>fun IndexBuffer.[setBuffer](set-buffer.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html))<br>fun IndexBuffer.[setBuffer](set-buffer.md)(buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), destOffsetInBytes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setBufferAt](set-buffer-at.md) | [androidJvm]<br>fun VertexBuffer.[setBufferAt](set-buffer-at.md)(bufferIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html))<br>fun VertexBuffer.[setBufferAt](set-buffer-at.md)(bufferIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), destOffsetInBytes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setMaterial](set-material.md) | [androidJvm]<br>fun [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[setMaterial](set-material.md)(material: MaterialInstance) |
| [setMaterialAt](set-material-at.md) | [androidJvm]<br>fun [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[setMaterialAt](set-material-at.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)primitiveIndex: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), material: MaterialInstance) |
| [setPriority](set-priority.md) | [androidJvm]<br>fun [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[setPriority](set-priority.md)(@[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 7)priority: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [instance](instance.md) | [androidJvm]<br>val [Renderable](index.md#286838466%2FClasslikes%2F-1571379623).[instance](instance.md): [RenderableInstance](index.md#841054893%2FClasslikes%2F-1571379623) |
| [RENDER_PRIORITY_DEFAULT](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md) | [androidJvm]<br>const val [RENDER_PRIORITY_DEFAULT](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-d-e-f-a-u-l-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [RENDER_PRIORITY_FIRST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md) | [androidJvm]<br>const val [RENDER_PRIORITY_FIRST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-f-i-r-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [RENDER_PRIORITY_LAST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md) | [androidJvm]<br>const val [RENDER_PRIORITY_LAST](-r-e-n-d-e-r_-p-r-i-o-r-i-t-y_-l-a-s-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 7 |
