//[sceneview](../../../index.md)/[io.github.sceneview.environment](../index.md)/[IBLPrefilter](index.md)/[specularFilter](specular-filter.md)

# specularFilter

[androidJvm]\
fun [specularFilter](specular-filter.md)(skybox: Texture): Texture

###  Generates a prefiltered cubemap.

SpecularFilter is a GPU based implementation of the specular probe pre-integration filter.

** Launch the heaver computation. Expect 100-100ms on the GPU.**

#### Return

the reflections texture

## Parameters

androidJvm

| | |
|---|---|
| skybox | Environment cubemap. This cubemap is SAMPLED and have all its levels allocated. |
