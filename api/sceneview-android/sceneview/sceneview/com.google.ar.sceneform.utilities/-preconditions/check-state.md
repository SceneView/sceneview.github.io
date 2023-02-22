//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[Preconditions](index.md)/[checkState](check-state.md)

# checkState

[androidJvm]\
open fun [checkState](check-state.md)(expression: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Ensures the truth of an expression involving the state of the calling instance, but not involving any parameters to the calling method.

## Parameters

androidJvm

| | |
|---|---|
| expression | a boolean expression |

## Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://developer.android.com/reference/kotlin/java/lang/IllegalStateException.html) | if `expression` is false |

[androidJvm]\
open fun [checkState](check-state.md)(expression: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)errorMessage: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))

Ensures the truth of an expression involving the state of the calling instance, but not involving any parameters to the calling method.

## Parameters

androidJvm

| | |
|---|---|
| expression | a boolean expression |
| errorMessage | the exception message to use if the check fails; will be converted to a string using [valueOf](https://developer.android.com/reference/kotlin/java/lang/String.html#valueof) |

## Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://developer.android.com/reference/kotlin/java/lang/IllegalStateException.html) | if `expression` is false |
