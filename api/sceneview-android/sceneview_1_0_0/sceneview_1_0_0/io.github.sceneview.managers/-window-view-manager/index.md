//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.managers](../index.md)/[WindowViewManager](index.md)

# WindowViewManager

[androidJvm]\
class [WindowViewManager](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pxPerUnits: () -&gt; [Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187))

Manages a [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached directly to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) that other views can be added and removed from.

To render a [View](https://developer.android.com/reference/kotlin/android/view/View.html), the [View](https://developer.android.com/reference/kotlin/android/view/View.html) must be attached to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) so that it can be properly drawn. This class encapsulates a [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) that other views can be added to as children. This allows us to safely and correctly draw the [View](https://developer.android.com/reference/kotlin/android/view/View.html) associated with a [RenderableManager](../../io.github.sceneview/index.md#1934583341%2FClasslikes%2F-602047187) and a MaterialInstance while keeping them isolated from the rest of the activities View hierarchy.

Additionally, this manages the lifecycle of the window to help ensure that the window is added/removed from the WindowManager at the appropriate times.

## Parameters

androidJvm

| | |
|---|---|
| width | The container width (used in case of MATCH_PARENT child) |
| height | The container height (used in case of MATCH_PARENT child) |
| pxPerUnits | The number of pixels within a unit. This value should be updated by a SceneView |

## Constructors

| | |
|---|---|
| [WindowViewManager](-window-view-manager.md) | [androidJvm]<br>fun [WindowViewManager](-window-view-manager.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md)) |
| [WindowViewManager](-window-view-manager.md) | [androidJvm]<br>fun [WindowViewManager](-window-view-manager.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pxPerUnits: () -&gt; [Size](../../io.github.sceneview.math/index.md#1872733609%2FClasslikes%2F-602047187)) |

## Functions

| Name | Summary |
|---|---|
| [addView](add-view.md) | [androidJvm]<br>fun [addView](add-view.md)(view: [ViewStream](../../io.github.sceneview.texture/-view-stream/index.md))<br>Add a [View](https://developer.android.com/reference/kotlin/android/view/View.html) as a child of the [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to the [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html). |
| [destroy](destroy.md) | [androidJvm]<br>fun [destroy](destroy.md)() |
| [pause](pause.md) | [androidJvm]<br>fun [pause](pause.md)()<br>The layout must be removed from the [windowManager](../../../../sceneview_1_0_0/io.github.sceneview.managers/-window-view-manager/window-manager.md) before the activity is destroyed, or the window will be leaked. Therefore we add/remove the ownerView in resume/pause. |
| [removeView](remove-view.md) | [androidJvm]<br>fun [removeView](remove-view.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html))<br>Remove a [View](https://developer.android.com/reference/kotlin/android/view/View.html) from the [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to the [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html). |
| [resume](resume.md) | [androidJvm]<br>fun [resume](resume.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html))<br>An owner View can only be added to the WindowManager after the activity has finished resuming. Therefore, we must use post to ensure that the window is only added after resume is finished. |
| [setSize](set-size.md) | [androidJvm]<br>fun [setSize](set-size.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>The container size (used in case of MATCH_PARENT child) |
