//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[HeadlessEngineWrapper](index.md)

# HeadlessEngineWrapper

[androidJvm]\
open class [HeadlessEngineWrapper](index.md) : [FilamentEngineWrapper](../-filament-engine-wrapper/index.md)

Interface for the swiftshader backed version of the Filament engine.

## Constructors

| | |
|---|---|
| [HeadlessEngineWrapper](-headless-engine-wrapper.md) | [androidJvm]<br>open fun [HeadlessEngineWrapper](-headless-engine-wrapper.md)() |

## Functions

| Name | Summary |
|---|---|
| [createCamera](../-filament-engine-wrapper/create-camera.md) | [androidJvm]<br>open fun [createCamera](../-filament-engine-wrapper/create-camera.md)(): Camera<br>open fun [createCamera](../-filament-engine-wrapper/create-camera.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Camera<br>abstract fun [createCamera](../-i-engine/create-camera.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Camera |
| [createFence](../-filament-engine-wrapper/create-fence.md) | [androidJvm]<br>open fun [createFence](../-filament-engine-wrapper/create-fence.md)(): Fence |
| [createRenderer](../-filament-engine-wrapper/create-renderer.md) | [androidJvm]<br>open fun [createRenderer](../-filament-engine-wrapper/create-renderer.md)(): Renderer |
| [createScene](../-filament-engine-wrapper/create-scene.md) | [androidJvm]<br>open fun [createScene](../-filament-engine-wrapper/create-scene.md)(): Scene |
| [createSwapChain](create-swap-chain.md) | [androidJvm]<br>open fun [createSwapChain](create-swap-chain.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none<br>[androidJvm]<br>open fun [createSwapChain](create-swap-chain.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none Flags: see CONFIG flags in SwapChain. |
| [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md) | [androidJvm]<br>open fun [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)surface: NativeSurface, flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain |
| [createView](../-filament-engine-wrapper/create-view.md) | [androidJvm]<br>open fun [createView](../-filament-engine-wrapper/create-view.md)(): View |
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |
| [destroyEntity](../-filament-engine-wrapper/destroy-entity.md) | [androidJvm]<br>open fun [destroyEntity](../-filament-engine-wrapper/destroy-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>abstract fun [destroyEntity](../-i-engine/destroy-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [destroyFence](../-filament-engine-wrapper/destroy-fence.md) | [androidJvm]<br>open fun [destroyFence](../-filament-engine-wrapper/destroy-fence.md)(fence: Fence) |
| [destroyIndexBuffer](../-filament-engine-wrapper/destroy-index-buffer.md) | [androidJvm]<br>open fun [destroyIndexBuffer](../-filament-engine-wrapper/destroy-index-buffer.md)(indexBuffer: IndexBuffer) |
| [destroyIndirectLight](../-filament-engine-wrapper/destroy-indirect-light.md) | [androidJvm]<br>open fun [destroyIndirectLight](../-filament-engine-wrapper/destroy-indirect-light.md)(ibl: IndirectLight) |
| [destroyMaterial](../-filament-engine-wrapper/destroy-material.md) | [androidJvm]<br>open fun [destroyMaterial](../-filament-engine-wrapper/destroy-material.md)(material: Material) |
| [destroyMaterialInstance](../-filament-engine-wrapper/destroy-material-instance.md) | [androidJvm]<br>open fun [destroyMaterialInstance](../-filament-engine-wrapper/destroy-material-instance.md)(materialInstance: MaterialInstance) |
| [destroyRenderer](../-filament-engine-wrapper/destroy-renderer.md) | [androidJvm]<br>open fun [destroyRenderer](../-filament-engine-wrapper/destroy-renderer.md)(renderer: Renderer) |
| [destroyScene](../-filament-engine-wrapper/destroy-scene.md) | [androidJvm]<br>open fun [destroyScene](../-filament-engine-wrapper/destroy-scene.md)(scene: Scene) |
| [destroySkybox](../-filament-engine-wrapper/destroy-skybox.md) | [androidJvm]<br>open fun [destroySkybox](../-filament-engine-wrapper/destroy-skybox.md)(skybox: Skybox) |
| [destroyStream](../-filament-engine-wrapper/destroy-stream.md) | [androidJvm]<br>open fun [destroyStream](../-filament-engine-wrapper/destroy-stream.md)(stream: Stream) |
| [destroySwapChain](destroy-swap-chain.md) | [androidJvm]<br>open fun [destroySwapChain](destroy-swap-chain.md)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)swapChain: SwapChain) |
| [destroyTexture](../-filament-engine-wrapper/destroy-texture.md) | [androidJvm]<br>open fun [destroyTexture](../-filament-engine-wrapper/destroy-texture.md)(texture: Texture) |
| [destroyVertexBuffer](../-filament-engine-wrapper/destroy-vertex-buffer.md) | [androidJvm]<br>open fun [destroyVertexBuffer](../-filament-engine-wrapper/destroy-vertex-buffer.md)(vertexBuffer: VertexBuffer) |
| [destroyView](../-filament-engine-wrapper/destroy-view.md) | [androidJvm]<br>open fun [destroyView](../-filament-engine-wrapper/destroy-view.md)(view: View) |
| [flushAndWait](../-filament-engine-wrapper/flush-and-wait.md) | [androidJvm]<br>open fun [flushAndWait](../-filament-engine-wrapper/flush-and-wait.md)() |
| [getFilamentEngine](../-filament-engine-wrapper/get-filament-engine.md) | [androidJvm]<br>open fun [getFilamentEngine](../-filament-engine-wrapper/get-filament-engine.md)(): Engine |
| [getLightManager](../-filament-engine-wrapper/get-light-manager.md) | [androidJvm]<br>open fun [getLightManager](../-filament-engine-wrapper/get-light-manager.md)(): LightManager |
| [getRenderableManager](../-filament-engine-wrapper/get-renderable-manager.md) | [androidJvm]<br>open fun [getRenderableManager](../-filament-engine-wrapper/get-renderable-manager.md)(): RenderableManager |
| [getTransformManager](../-filament-engine-wrapper/get-transform-manager.md) | [androidJvm]<br>open fun [getTransformManager](../-filament-engine-wrapper/get-transform-manager.md)(): TransformManager |
| [isValid](../-filament-engine-wrapper/is-valid.md) | [androidJvm]<br>open fun [isValid](../-filament-engine-wrapper/is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [TAG](-t-a-g.md) | [androidJvm]<br>val [TAG](-t-a-g.md): [String](https://developer.android.com/reference/kotlin/java/lang/String.html) |
