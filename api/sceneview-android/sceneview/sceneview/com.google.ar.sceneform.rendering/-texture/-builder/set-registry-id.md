//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Texture](../index.md)/[Builder](index.md)/[setRegistryId](set-registry-id.md)

# setRegistryId

[androidJvm]\
open fun [setRegistryId](set-registry-id.md)(registryId: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Texture.Builder](index.md)

Allows a [Texture](../index.md) to be reused. If registryId is non-null it will be saved in a registry and the registry will be checked for this id before construction.

#### Return

[Builder](index.md) for chaining setup calls.

## Parameters

androidJvm

| | |
|---|---|
| registryId | Allows the function to be skipped and a previous texture to be re-used. |
