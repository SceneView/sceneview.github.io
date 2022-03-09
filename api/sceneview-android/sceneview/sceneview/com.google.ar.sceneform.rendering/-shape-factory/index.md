//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ShapeFactory](index.md)

# ShapeFactory

[androidJvm]\
@[RequiresApi](https://developer.android.com/reference/kotlin/androidx/annotation/RequiresApi.html)(api = [Build.VERSION_CODES.N](https://developer.android.com/reference/kotlin/android/os/Build.VERSION_CODES.html))

class [ShapeFactory](index.md)

Utility class used to dynamically construct [ModelRenderable](../-model-renderable/index.md)s for various shapes.

## Functions

| Name | Summary |
|---|---|
| [makeCube](make-cube.md) | [androidJvm]<br>open fun [makeCube](make-cube.md)(size: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), center: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), material: [Material](../-material/index.md)): [ModelRenderable](../-model-renderable/index.md)<br>Creates a [ModelRenderable](../-model-renderable/index.md) in the shape of a cube with the give specifications. |
| [makeCylinder](make-cylinder.md) | [androidJvm]<br>open fun [makeCylinder](make-cylinder.md)(radius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), height: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), center: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), material: [Material](../-material/index.md)): [ModelRenderable](../-model-renderable/index.md)<br>Creates a [ModelRenderable](../-model-renderable/index.md) in the shape of a cylinder with the give specifications. |
| [makeSphere](make-sphere.md) | [androidJvm]<br>open fun [makeSphere](make-sphere.md)(radius: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), center: [Vector3](../../com.google.ar.sceneform.math/-vector3/index.md), material: [Material](../-material/index.md)): [ModelRenderable](../-model-renderable/index.md)<br>Creates a [ModelRenderable](../-model-renderable/index.md) in the shape of a sphere with the give specifications. |
