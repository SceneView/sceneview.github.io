//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[ChangeId](index.md)

# ChangeId

[androidJvm]\
open class [ChangeId](index.md)

Used to identify when the state of an object has changed by incrementing an integer id. Other classes can determine when this object has changed by polling to see if the id has changed. 

This is useful as an alternative to an event listener subscription model when there is no safe point in the lifecycle of an object to unsubscribe from the event listeners. Unlike event listeners, this cannot cause memory leaks.

## Functions

| Name | Summary |
|---|---|
| [checkChanged](check-changed.md) | [androidJvm]<br>open fun [checkChanged](check-changed.md)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](get.md) | [androidJvm]<br>open fun [get](get.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](is-empty.md) | [androidJvm]<br>open fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [update](update.md) | [androidJvm]<br>open fun [update](update.md)() |

## Properties

| Name | Summary |
|---|---|
| [EMPTY_ID](-e-m-p-t-y_-i-d.md) | [androidJvm]<br>val [EMPTY_ID](-e-m-p-t-y_-i-d.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
