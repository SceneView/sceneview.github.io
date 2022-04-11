//[arsceneview](../../../index.md)/[io.github.sceneview.ar.node](../index.md)/[ArNode](index.md)/[hostCloudAnchor](host-cloud-anchor.md)

# hostCloudAnchor

[androidJvm]\
fun [hostCloudAnchor](host-cloud-anchor.md)(ttlDays: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, onTaskCompleted: (anchor: Anchor, success: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Hosts a Cloud Anchor based on the [anchor](anchor.md)

The [anchor](anchor.md) is replaced with a new anchor returned by [Session.hostCloudAnchorWithTtl](../../io.github.sceneview.ar.arcore/-ar-session/index.md#778488847%2FFunctions%2F-58641720).

## Parameters

androidJvm

| | |
|---|---|
| ttlDays | The lifetime of the anchor in days. See [Session.hostCloudAnchorWithTtl](../../io.github.sceneview.ar.arcore/-ar-session/index.md#778488847%2FFunctions%2F-58641720) for more details. |
| onTaskCompleted | Called when the task completes successfully or with an error. |
