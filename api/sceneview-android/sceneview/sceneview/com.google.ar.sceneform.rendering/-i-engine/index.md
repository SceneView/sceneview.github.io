//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[IEngine](index.md)

# IEngine

[androidJvm]\
interface [IEngine](index.md)

Engine interface to support multiple flavors of the getFilamentEngine filament engine.

## Functions

| Name | Summary |
|---|---|
| [createCamera](create-camera.md) | [androidJvm]<br>abstract fun [createCamera](create-camera.md)(): Camera<br>abstract fun [createCamera](create-camera.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): Camera |
| [createFence](create-fence.md) | [androidJvm]<br>abstract fun [createFence](create-fence.md)(): Fence |
| [createRenderer](create-renderer.md) | [androidJvm]<br>abstract fun [createRenderer](create-renderer.md)(): Renderer |
| [createScene](create-scene.md) | [androidJvm]<br>abstract fun [createScene](create-scene.md)(): Scene |
| [createSwapChain](create-swap-chain.md) | [androidJvm]<br>abstract fun [createSwapChain](create-swap-chain.md)(surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none<br>[androidJvm]<br>abstract fun [createSwapChain](create-swap-chain.md)(surface: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain<br>Valid surface types: - Android: Surface - Other: none Flags: see CONFIG flags in SwapChain. |
| [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md) | [androidJvm]<br>abstract fun [createSwapChainFromNativeSurface](create-swap-chain-from-native-surface.md)(surface: NativeSurface, flags: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): SwapChain |
| [createView](create-view.md) | [androidJvm]<br>abstract fun [createView](create-view.md)(): View |
| [destroy](destroy.md) | [androidJvm]<br>abstract fun [destroy](destroy.md)() |
| [destroyEntity](destroy-entity.md) | [androidJvm]<br>abstract fun [destroyEntity](destroy-entity.md)(entity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [destroyFence](destroy-fence.md) | [androidJvm]<br>abstract fun [destroyFence](destroy-fence.md)(fence: Fence) |
| [destroyIndexBuffer](destroy-index-buffer.md) | [androidJvm]<br>abstract fun [destroyIndexBuffer](destroy-index-buffer.md)(indexBuffer: IndexBuffer) |
| [destroyIndirectLight](destroy-indirect-light.md) | [androidJvm]<br>abstract fun [destroyIndirectLight](destroy-indirect-light.md)(ibl: IndirectLight) |
| [destroyMaterial](destroy-material.md) | [androidJvm]<br>abstract fun [destroyMaterial](destroy-material.md)(material: Material) |
| [destroyMaterialInstance](destroy-material-instance.md) | [androidJvm]<br>abstract fun [destroyMaterialInstance](destroy-material-instance.md)(materialInstance: MaterialInstance) |
| [destroyRenderer](destroy-renderer.md) | [androidJvm]<br>abstract fun [destroyRenderer](destroy-renderer.md)(renderer: Renderer) |
| [destroyScene](destroy-scene.md) | [androidJvm]<br>abstract fun [destroyScene](destroy-scene.md)(scene: Scene) |
| [destroySkybox](destroy-skybox.md) | [androidJvm]<br>abstract fun [destroySkybox](destroy-skybox.md)(skybox: Skybox) |
| [destroyStream](destroy-stream.md) | [androidJvm]<br>abstract fun [destroyStream](destroy-stream.md)(stream: Stream) |
| [destroySwapChain](destroy-swap-chain.md) | [androidJvm]<br>abstract fun [destroySwapChain](destroy-swap-chain.md)(swapChain: SwapChain) |
| [destroyTexture](destroy-texture.md) | [androidJvm]<br>abstract fun [destroyTexture](destroy-texture.md)(texture: Texture) |
| [destroyVertexBuffer](destroy-vertex-buffer.md) | [androidJvm]<br>abstract fun [destroyVertexBuffer](destroy-vertex-buffer.md)(vertexBuffer: VertexBuffer) |
| [destroyView](destroy-view.md) | [androidJvm]<br>abstract fun [destroyView](destroy-view.md)(view: View) |
| [flushAndWait](flush-and-wait.md) | [androidJvm]<br>abstract fun [flushAndWait](flush-and-wait.md)() |
| [getFilamentEngine](get-filament-engine.md) | [androidJvm]<br>abstract fun [getFilamentEngine](get-filament-engine.md)(): Engine |
| [getLightManager](get-light-manager.md) | [androidJvm]<br>abstract fun [getLightManager](get-light-manager.md)(): LightManager |
| [getRenderableManager](get-renderable-manager.md) | [androidJvm]<br>abstract fun [getRenderableManager](get-renderable-manager.md)(): RenderableManager |
| [getTransformManager](get-transform-manager.md) | [androidJvm]<br>abstract fun [getTransformManager](get-transform-manager.md)(): TransformManager |
| [isValid](is-valid.md) | [androidJvm]<br>abstract fun [isValid](is-valid.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [FilamentEngineWrapper](../-filament-engine-wrapper/index.md) |
