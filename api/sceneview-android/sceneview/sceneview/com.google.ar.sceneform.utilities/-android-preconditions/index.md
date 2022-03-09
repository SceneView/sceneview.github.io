//[sceneview](../../../index.md)/[com.google.ar.sceneform.utilities](../index.md)/[AndroidPreconditions](index.md)

# AndroidPreconditions

[androidJvm]\
open class [AndroidPreconditions](index.md)

Helper class for common android specific preconditions used inside of RenderCore.

## Functions

| Name | Summary |
|---|---|
| [checkMinAndroidApiLevel](check-min-android-api-level.md) | [androidJvm]<br>open fun [checkMinAndroidApiLevel](check-min-android-api-level.md)()<br>Enforce the minimum Android api level |
| [checkUiThread](check-ui-thread.md) | [androidJvm]<br>open fun [checkUiThread](check-ui-thread.md)()<br>Ensure that the code is being executed on Android's UI thread. |
| [isAndroidApiAvailable](is-android-api-available.md) | [androidJvm]<br>open fun [isAndroidApiAvailable](is-android-api-available.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if the Android API is currently available. |
| [isMinAndroidApiLevel](is-min-android-api-level.md) | [androidJvm]<br>open fun [isMinAndroidApiLevel](is-min-android-api-level.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if the Android api level is above the minimum or if not on Android. |
| [setUnderTesting](set-under-testing.md) | [androidJvm]<br>open fun [setUnderTesting](set-under-testing.md)(isUnderTesting: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [isUnderTesting](is-under-testing.md) | [androidJvm]<br>private open val [isUnderTesting](is-under-testing.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
