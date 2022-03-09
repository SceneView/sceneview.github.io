//[arsceneview](../../index.md)/[io.github.sceneview.ar.arcore](index.md)/[firstValid](first-valid.md)

# firstValid

[androidJvm]\
fun [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)&lt;HitResult&gt;.[firstValid](first-valid.md)(camera: Camera, plane: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), depth: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), instantPlacement: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): HitResult?

###  Best HitResult within the list in precision terms

Hits are sorted by depth. Consider only closest hit on a plane, Oriented Point, Depth Point, or Instant Placement Point.
