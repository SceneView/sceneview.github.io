//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ArSceneView](index.md)/[configureSession](configure-session.md)

# configureSession

[androidJvm]\
fun [configureSession](configure-session.md)(applyConfig: ([ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), Config) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

###  Define the session config used by ARCore

Prefer calling this method before the global (Activity or Fragment) onResume() cause the session base configuration in made there. Any later calls (after onSessionResumed()) to this function are not completely sure be taken in account by ARCore (even if most of them will work)

Please check that all your Session Config parameters are taken in account by ARCore at runtime.

## Parameters

androidJvm

| | |
|---|---|
| applyConfig | the apply block for the new config |
