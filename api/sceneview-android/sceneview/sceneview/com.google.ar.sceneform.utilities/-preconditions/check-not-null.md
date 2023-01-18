//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[Preconditions](index.md)/[checkNotNull](check-not-null.md)

# checkNotNull

[androidJvm]\
open fun &lt;[T](check-not-null.md)&gt; [checkNotNull](check-not-null.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)reference: [T](../../../../arsceneview/com.google.ar.sceneform.rendering/-future-helper/log-on-exception.md)): [T](../../../../arsceneview/com.google.ar.sceneform.rendering/-future-helper/log-on-exception.md)

Ensures that an object reference passed as a parameter to the calling method is not null.

## Parameters

androidJvm

| | |
|---|---|
| reference | an object reference |

## Throws

| | |
|---|---|
| [java.lang.NullPointerException](https://developer.android.com/reference/kotlin/java/lang/NullPointerException.html) | if `reference` is null |

[androidJvm]\
open fun &lt;[T](check-not-null.md)&gt; [checkNotNull](check-not-null.md)(@[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)reference: [T](../../../../arsceneview/com.google.ar.sceneform.rendering/-future-helper/log-on-exception.md), errorMessage: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](../../../../arsceneview/com.google.ar.sceneform.rendering/-future-helper/log-on-exception.md)

Ensures that an object reference passed as a parameter to the calling method is not null.

## Parameters

androidJvm

| | |
|---|---|
| reference | an object reference |
| errorMessage | the exception message to use if the check fails; will be converted to a string using [valueOf](https://developer.android.com/reference/kotlin/java/lang/String.html#valueof) |

## Throws

| | |
|---|---|
| [java.lang.NullPointerException](https://developer.android.com/reference/kotlin/java/lang/NullPointerException.html) | if `reference` is null |
