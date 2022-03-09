//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[Preconditions](index.md)/[checkElementIndex](check-element-index.md)

# checkElementIndex

[androidJvm]\
open fun [checkElementIndex](check-element-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Ensures that index specifies a valid *element* in an array, list or string of size size. An element index may range from zero, inclusive, to size, exclusive.

## Parameters

androidJvm

| | |
|---|---|
| index | a user-supplied index identifying an element of an array, list or string |
| size | the size of that array, list or string |

## Throws

| | |
|---|---|
| [java.lang.IndexOutOfBoundsException](https://developer.android.com/reference/kotlin/java/lang/IndexOutOfBoundsException.html) | if index is negative or is not less than size |
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | if size is negative |

[androidJvm]\
open fun [checkElementIndex](check-element-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), desc: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))

Ensures that index specifies a valid *element* in an array, list or string of size size. An element index may range from zero, inclusive, to size, exclusive.

## Parameters

androidJvm

| | |
|---|---|
| index | a user-supplied index identifying an element of an array, list or string |
| size | the size of that array, list or string |
| desc | the text to use to describe this index in an error message |

## Throws

| | |
|---|---|
| [java.lang.IndexOutOfBoundsException](https://developer.android.com/reference/kotlin/java/lang/IndexOutOfBoundsException.html) | if index is negative or is not less than size |
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | if size is negative |
