//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[FilamentEngineWrapper](index.md)

# FilamentEngineWrapper

[androidJvm]\
open class [FilamentEngineWrapper](index.md) : [IEngine](../-i-engine/index.md)

Wraps calls to Filament engine.

## Constructors

| | |
|---|---|
| [FilamentEngineWrapper](-filament-engine-wrapper.md) | [androidJvm]<br>open fun [FilamentEngineWrapper](-filament-engine-wrapper.md)(engine: Engine) |

## Functions

| Name | Summary |
|---|---|
| [createCamera](create-camera.md) | [androidJvm]<br>open fun [createCamera](create-camera.md)(): Camera<br>open fun [createCamera](create-camera.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Camera |
| [createFence](create-fence.md) | [androidJvm]<br>open fun [createFence](create-fence.md)(): Fence |
| [createRenderer](create-renderer.md) | [androidJvm]<br>open fun [createRenderer](create-renderer.md)(): Renderer |
| [createScene](create-scene.md) | [androidJvm]<br>open fun [createScene](create-scene.md)(): Scene |
| [createSwapChain](create-swap-chain.md) | [androidJvm]<br>open fun [createSwapChain](create-swap-chain.md)(surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none<br>[androidJvm]<br>open fun [createSwapChain](create-swap-chain.md)(surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none Flags: see CONFIG flags in SwapChain. |
| [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md) | [androidJvm]<br>open fun [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md)(surface: NativeSurface, flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain |
| [createView](create-view.md) | [androidJvm]<br>open fun [createView](create-view.md)(): View |
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |
| [destroyEntity](destroy-entity.md) | [androidJvm]<br>open fun [destroyEntity](destroy-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [destroyFence](destroy-fence.md) | [androidJvm]<br>open fun [destroyFence](destroy-fence.md)(fence: Fence) |
| [destroyIndexBuffer](destroy-index-buffer.md) | [androidJvm]<br>open fun [destroyIndexBuffer](destroy-index-buffer.md)(indexBuffer: IndexBuffer) |
| [destroyIndirectLight](destroy-indirect-light.md) | [androidJvm]<br>open fun [destroyIndirectLight](destroy-indirect-light.md)(ibl: IndirectLight) |
| [destroyMaterial](destroy-material.md) | [androidJvm]<br>open fun [destroyMaterial](destroy-material.md)(material: Material) |
| [destroyMaterialInstance](destroy-material-instance.md) | [androidJvm]<br>open fun [destroyMaterialInstance](destroy-material-instance.md)(materialInstance: MaterialInstance) |
| [destroyRenderer](destroy-renderer.md) | [androidJvm]<br>open fun [destroyRenderer](destroy-renderer.md)(renderer: Renderer) |
| [destroyScene](destroy-scene.md) | [androidJvm]<br>open fun [destroyScene](destroy-scene.md)(scene: Scene) |
| [destroySkybox](destroy-skybox.md) | [androidJvm]<br>open fun [destroySkybox](destroy-skybox.md)(skybox: Skybox) |
| [destroyStream](destroy-stream.md) | [androidJvm]<br>open fun [destroyStream](destroy-stream.md)(stream: Stream) |
| [destroySwapChain](destroy-swap-chain.md) | [androidJvm]<br>open fun [destroySwapChain](destroy-swap-chain.md)(swapChain: SwapChain) |
| [destroyTexture](destroy-texture.md) | [androidJvm]<br>open fun [destroyTexture](destroy-texture.md)(texture: Texture) |
| [destroyVertexBuffer](destroy-vertex-buffer.md) | [androidJvm]<br>open fun [destroyVertexBuffer](destroy-vertex-buffer.md)(vertexBuffer: VertexBuffer) |
| [destroyView](destroy-view.md) | [androidJvm]<br>open fun [destroyView](destroy-view.md)(view: View) |
| [flushAndWait](flush-and-wait.md) | [androidJvm]<br>open fun [flushAndWait](flush-and-wait.md)() |
| [getFilamentEngine](get-filament-engine.md) | [androidJvm]<br>open fun [getFilamentEngine](get-filament-engine.md)(): Engine |
| [getLightManager](get-light-manager.md) | [androidJvm]<br>open fun [getLightManager](get-light-manager.md)(): LightManager |
| [getRenderableManager](get-renderable-manager.md) | [androidJvm]<br>open fun [getRenderableManager](get-renderable-manager.md)(): RenderableManager |
| [getTransformManager](get-transform-manager.md) | [androidJvm]<br>open fun [getTransformManager](get-transform-manager.md)(): TransformManager |
| [isValid](is-valid.md) | [androidJvm]<br>open fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [HeadlessEngineWrapper](../-headless-engine-wrapper/index.md) |
