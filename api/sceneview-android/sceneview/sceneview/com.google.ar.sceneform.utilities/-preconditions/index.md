//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[Preconditions](index.md)

# Preconditions

[androidJvm]\
open class [Preconditions](index.md)

Static convenience methods that help a method or constructor check whether it was invoked correctly.

## Functions

| Name | Summary |
|---|---|
| [checkElementIndex](check-element-index.md) | [androidJvm]<br>open fun [checkElementIndex](check-element-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [checkElementIndex](check-element-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), desc: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Ensures that `index` specifies a valid *element* in an array, list or string of size `size`. |
| [checkNotNull](check-not-null.md) | [androidJvm]<br>open fun &lt;[T](check-not-null.md)&gt; [checkNotNull](check-not-null.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)reference: [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)): [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)<br>open fun &lt;[T](check-not-null.md)&gt; [checkNotNull](check-not-null.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)reference: [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md), errorMessage: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](../../com.google.ar.sceneform.resources/-resource-registry/index.md)<br>Ensures that an object reference passed as a parameter to the calling method is not null. |
| [checkState](check-state.md) | [androidJvm]<br>open fun [checkState](check-state.md)(expression: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>open fun [checkState](check-state.md)(expression: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)errorMessage: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))<br>Ensures the truth of an expression involving the state of the calling instance, but not involving any parameters to the calling method. |
