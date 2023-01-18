//[sceneview](../../../index.md)/[com.google.ar.sceneform.rendering](../index.md)/[ViewAttachmentManager](index.md)

# ViewAttachmentManager

[androidJvm]\
open class [ViewAttachmentManager](index.md)

Manages a [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached directly to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) that other views can be added and removed from. 

To render a [View](https://developer.android.com/reference/kotlin/android/view/View.html), the [View](https://developer.android.com/reference/kotlin/android/view/View.html) must be attached to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) so that it can be properly drawn. This class encapsulates a [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to a [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html) that other views can be added to as children. This allows us to safely and correctly draw the [View](https://developer.android.com/reference/kotlin/android/view/View.html) associated with [ViewRenderable](../-view-renderable/index.md)'s while keeping them isolated from the rest of the activities View hierarchy. 

Additionally, this manages the lifecycle of the window to help ensure that the window is added/removed from the WindowManager at the appropriate times.

## Constructors

| | |
|---|---|
| [ViewAttachmentManager](-view-attachment-manager.md) | [androidJvm]<br>open fun [ViewAttachmentManager](-view-attachment-manager.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), ownerView: [View](https://developer.android.com/reference/kotlin/android/view/View.html))<br>Construct a ViewAttachmentManager. |

## Functions

| Name | Summary |
|---|---|
| [addView](add-view.md) | [androidJvm]<br>open fun [addView](add-view.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html))<br>Add a ownerView as a child of the [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to the . |
| [onPause](on-pause.md) | [androidJvm]<br>open fun [onPause](on-pause.md)() |
| [onResume](on-resume.md) | [androidJvm]<br>open fun [onResume](on-resume.md)() |
| [removeView](remove-view.md) | [androidJvm]<br>open fun [removeView](remove-view.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html))<br>Remove a ownerView from the [FrameLayout](https://developer.android.com/reference/kotlin/android/widget/FrameLayout.html) that is attached to the [WindowManager](https://developer.android.com/reference/kotlin/android/view/WindowManager.html). |
