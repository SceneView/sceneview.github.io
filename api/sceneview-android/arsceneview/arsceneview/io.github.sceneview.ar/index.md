//[arsceneview](../../index.md)/[io.github.sceneview.ar](index.md)

# Package io.github.sceneview.ar

## Types

| Name | Summary |
|---|---|
| [ARCore](-a-r-core/index.md) | [androidJvm]<br>class [ARCore](-a-r-core/index.md)(lifecycle: [ArSceneLifecycle](-ar-scene-lifecycle/index.md), features: () -&gt; [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt;) : [ArSceneLifecycleObserver](-ar-scene-lifecycle-observer/index.md)<br>Manages an ARCore Session using the Android Lifecycle API. Before starting a Session, this class requests installation of Google Play Services for AR if it's not installed or not up to date and asks the user for required permissions if necessary. |
| [ArFragment](-ar-fragment/index.md) | [androidJvm]<br>~~class~~ [~~ArFragment~~](-ar-fragment/index.md) ~~:~~ [~~BaseArFragment~~](-base-ar-fragment/index.md) |
| [ArSceneLifecycle](-ar-scene-lifecycle/index.md) | [androidJvm]<br>class [ArSceneLifecycle](-ar-scene-lifecycle/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), owner: [ArSceneLifecycleOwner](-ar-scene-lifecycle-owner/index.md)) : [SceneLifecycle](../../../sceneview/sceneview/io.github.sceneview/-scene-lifecycle/index.md) |
| [ArSceneLifecycleObserver](-ar-scene-lifecycle-observer/index.md) | [androidJvm]<br>interface [ArSceneLifecycleObserver](-ar-scene-lifecycle-observer/index.md) : [SceneLifecycleObserver](../../../sceneview/sceneview/io.github.sceneview/-scene-lifecycle-observer/index.md) |
| [ArSceneLifecycleOwner](-ar-scene-lifecycle-owner/index.md) | [androidJvm]<br>interface [ArSceneLifecycleOwner](-ar-scene-lifecycle-owner/index.md) : [SceneLifecycleOwner](../../../sceneview/sceneview/io.github.sceneview/-scene-lifecycle-owner/index.md) |
| [ArSceneView](-ar-scene-view/index.md) | [androidJvm]<br>open class [ArSceneView](-ar-scene-view/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), attrs: [AttributeSet](https://developer.android.com/reference/kotlin/android/util/AttributeSet.html)?, defStyleAttr: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), defStyleRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [SceneView](../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md), [ArSceneLifecycleOwner](-ar-scene-lifecycle-owner/index.md), [ArSceneLifecycleObserver](-ar-scene-lifecycle-observer/index.md)<br>A SurfaceView that integrates with ARCore and renders a scene. |
| [BaseArFragment](-base-ar-fragment/index.md) | [androidJvm]<br>~~open~~ ~~class~~ [~~BaseArFragment~~](-base-ar-fragment/index.md) |
| [Instructions](-instructions/index.md) | [androidJvm]<br>class [Instructions](-instructions/index.md)(sceneView: [SceneView](../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md), lifecycle: [ArSceneLifecycle](-ar-scene-lifecycle/index.md)) : [ArSceneLifecycleObserver](-ar-scene-lifecycle-observer/index.md) |
| [Scene](-scene/index.md) | [androidJvm]<br>~~class~~ [~~Scene~~](-scene/index.md)<br>*=* [*SceneView*](../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md)*/*[*ArSceneView*](-ar-scene-view/index.md) *is a Scene (NodeParent)* that can contain |

## Functions

| Name | Summary |
|---|---|
| [addLifecycleListener](add-lifecycle-listener.md) | [androidJvm]<br>~~fun~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~addLifecycleListener~~](add-lifecycle-listener.md)~~(~~~~listener~~~~:~~ [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?~~)~~~~:~~ [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)? |
| [addTransformChangedListener](add-transform-changed-listener.md) | [androidJvm]<br>~~fun~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~addTransformChangedListener~~](add-transform-changed-listener.md)~~(~~~~listener~~~~:~~ [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?~~)~~~~:~~ [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)? |
| [configure](configure.md) | [androidJvm]<br>~~fun~~ Session~~.~~[~~configure~~](configure.md)~~(~~~~config~~~~:~~ Config~~)~~~~:~~ [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)? |
| [getConfig](get-config.md) | [androidJvm]<br>~~fun~~ Session~~.~~[~~getConfig~~](get-config.md)~~(~~~~)~~~~:~~ Config |
| [getScene](get-scene.md) | [androidJvm]<br>~~fun~~ [SceneView](../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md)~~.~~[~~getScene~~](get-scene.md)~~(~~~~)~~~~:~~ [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)?<br>*=* [*SceneView*](../../../sceneview/sceneview/io.github.sceneview/-scene-view/index.md)*/*[*ArSceneView*](-ar-scene-view/index.md) *is a Scene (NodeParent)* that can contain |
| [onUpdated](on-updated.md) | [androidJvm]<br>~~fun~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~onUpdated~~](on-updated.md)~~(~~~~node~~~~:~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~,~~ ~~frameTime~~~~:~~ [FrameTime](../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)~~)~~~~:~~ [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)? |

## Properties

| Name | Summary |
|---|---|
| [defaultApproximateDistanceMeters](default-approximate-distance-meters.md) | [androidJvm]<br>const val [defaultApproximateDistanceMeters](default-approximate-distance-meters.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 2.0f<br>This value affects the apparent scale of objects while the tracking method of the Instant Placement point is SCREENSPACE_WITH_APPROXIMATE_DISTANCE. Values in the 0.2, 2.0 meter range are a good choice for most AR experiences. Use lower values for AR experiences where users are expected to place objects on surfaces close to the camera. Use larger values for experiences where the user will likely be standing and trying to place an object on the ground or floor in front of them. |
| [isSelectable](is-selectable.md) | [androidJvm]<br>~~var~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~isSelectable~~](is-selectable.md)~~:~~ [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [localPosition](local-position.md) | [androidJvm]<br>~~var~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~localPosition~~](local-position.md)~~:~~ [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [localRotation](local-rotation.md) | [androidJvm]<br>~~var~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~localRotation~~](local-rotation.md)~~:~~ [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
| [localScale](local-scale.md) | [androidJvm]<br>~~var~~ [Node](../../../sceneview/sceneview/io.github.sceneview.node/-node/index.md)~~.~~[~~localScale~~](local-scale.md)~~:~~ [Float3](../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md) |
