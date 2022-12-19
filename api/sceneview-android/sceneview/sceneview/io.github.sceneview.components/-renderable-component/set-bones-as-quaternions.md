//[sceneview](../../../index.md)/[io.github.sceneview.components](../index.md)/[RenderableComponent](index.md)/[setBonesAsQuaternions](set-bones-as-quaternions.md)

# setBonesAsQuaternions

[androidJvm]\
open fun [setBonesAsQuaternions](set-bones-as-quaternions.md)(quaternions: [Buffer](https://docs.oracle.com/javase/8/docs/api/java/nio/Buffer.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0, to = 255)boneCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[IntRange](https://developer.android.com/reference/kotlin/androidx/annotation/IntRange.html)(from = 0)offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Sets the transforms associated with each bone of a Renderable

## See also

androidJvm

| | |
|---|---|
| com.google.android.filament.RenderableManager |  |

## Parameters

androidJvm

| | |
|---|---|
| quaternions | A FloatBuffer containing boneCount transforms. Each transform consists of 8 float. float 0 to 3 encode a unit quaternion w+ix+jy+kz stored as x,y,z,w. float 4 to 7 encode a translation stored as x,y,z,1 |
| boneCount | Number of bones to set |
| offset | Index of the first bone to set |
