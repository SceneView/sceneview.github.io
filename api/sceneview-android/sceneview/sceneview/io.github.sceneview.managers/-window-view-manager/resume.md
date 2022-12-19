//[sceneview](../../../index.md)/[io.github.sceneview.managers](../index.md)/[WindowViewManager](index.md)/[resume](resume.md)

# resume

[androidJvm]\
fun [resume](resume.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html))

An owner View can only be added to the WindowManager after the activity has finished resuming. Therefore, we must use post to ensure that the window is only added after resume is finished.
