//[sceneview](../../index.md)/[io.github.sceneview.environment](index.md)/[createIndirectLight](create-indirect-light.md)

# createIndirectLight

[androidJvm]\
fun KTXLoader.[createIndirectLight](create-indirect-light.md)(lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), buffer: [Buffer](https://developer.android.com/reference/kotlin/java/nio/Buffer.html), options: KTXLoader.Options = KTXLoader.Options()): IndirectLight

###  Consumes the content of a KTX file and produces an IndirectLight object.

#### Return

The resulting Filament texture, or null on failure.

## Parameters

androidJvm

| | |
|---|---|
| buffer | The content of the KTX File. |
| options | Loader options. |
