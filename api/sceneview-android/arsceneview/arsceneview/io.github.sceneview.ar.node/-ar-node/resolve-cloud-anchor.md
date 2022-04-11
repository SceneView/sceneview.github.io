//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[resolveCloudAnchor](resolve-cloud-anchor.md)

# resolveCloudAnchor

[androidJvm]\
fun [resolveCloudAnchor](resolve-cloud-anchor.md)(cloudAnchorId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), onTaskCompleted: (anchor: Anchor, success: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Resolves a Cloud Anchor

The [anchor](anchor.md) is replaced with a new anchor returned by [Session.resolveCloudAnchor](../../io.github.sceneview.ar.arcore/-ar-session/index.md#221260089%2FFunctions%2F-58641720).

## Parameters

androidJvm

| | |
|---|---|
| cloudAnchorId | The Cloud Anchor ID of the Cloud Anchor. |
| onTaskCompleted | Called when the task completes successfully or with an error. |
