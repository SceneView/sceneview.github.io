//[arsceneview](../../../index.md)/[io.github.sceneview.ar](../index.md)/[ARCore](index.md)

# ARCore

[androidJvm]\
class [ARCore](index.md)(lifecycle: [ArSceneLifecycle](../-ar-scene-lifecycle/index.md), features: () -&gt; [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt;) : [ArSceneLifecycleObserver](../-ar-scene-lifecycle-observer/index.md)

Manages an ARCore Session using the Android Lifecycle API. Before starting a Session, this class requests installation of Google Play Services for AR if it's not installed or not up to date and asks the user for required permissions if necessary.

## Constructors

| | |
|---|---|
| [ARCore](-a-r-core.md) | [androidJvm]<br>fun [ARCore](-a-r-core.md)(lifecycle: [ArSceneLifecycle](../-ar-scene-lifecycle/index.md), features: () -&gt; [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt; = { setOf() }) |

## Functions

| Name | Summary |
|---|---|
| [checkCameraPermission](check-camera-permission.md) | [androidJvm]<br>fun [checkCameraPermission](check-camera-permission.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), permissionLauncher: [ActivityResultLauncher](https://developer.android.com/reference/kotlin/androidx/activity/result/ActivityResultLauncher.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [checkInstall](check-install.md) | [androidJvm]<br>fun [checkInstall](check-install.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), installRequested: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [createSession](create-session.md) | [androidJvm]<br>fun [createSession](create-session.md)(lifecycle: [ArSceneLifecycle](../-ar-scene-lifecycle/index.md), features: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt; = setOf()): [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md) |
| [hasCameraPermission](has-camera-permission.md) | [androidJvm]<br>fun [hasCameraPermission](has-camera-permission.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check to see we have the necessary permissions for this app. |
| [install](install.md) | [androidJvm]<br>fun [install](install.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html), installRequested: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isInstalled](is-installed.md) | [androidJvm]<br>fun [isInstalled](is-installed.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check to see we have the necessary permissions for this app. |
| [onArFrame](../-ar-scene-lifecycle-observer/on-ar-frame.md) | [androidJvm]<br>open fun [onArFrame](../-ar-scene-lifecycle-observer/on-ar-frame.md)(arFrame: [ArFrame](../../io.github.sceneview.ar.arcore/-ar-frame/index.md)) |
| [onArSessionConfigChanged](../-ar-scene-lifecycle-observer/on-ar-session-config-changed.md) | [androidJvm]<br>open fun [onArSessionConfigChanged](../-ar-scene-lifecycle-observer/on-ar-session-config-changed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md), config: Config) |
| [onArSessionCreated](../-ar-scene-lifecycle-observer/on-ar-session-created.md) | [androidJvm]<br>open fun [onArSessionCreated](../-ar-scene-lifecycle-observer/on-ar-session-created.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onArSessionFailed](../-ar-scene-lifecycle-observer/on-ar-session-failed.md) | [androidJvm]<br>open fun [onArSessionFailed](../-ar-scene-lifecycle-observer/on-ar-session-failed.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onArSessionResumed](../-ar-scene-lifecycle-observer/on-ar-session-resumed.md) | [androidJvm]<br>open fun [onArSessionResumed](../-ar-scene-lifecycle-observer/on-ar-session-resumed.md)(session: [ArSession](../../io.github.sceneview.ar.arcore/-ar-session/index.md)) |
| [onCreate](on-create.md) | [androidJvm]<br>open override fun [onCreate](on-create.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](on-destroy.md) | [androidJvm]<br>open override fun [onDestroy](on-destroy.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html))<br>Review the API reference for important considerations before calling close() in apps with more complicated lifecycle requirements: [Session.close](../../io.github.sceneview.ar.arcore/-ar-session/index.md#-495079079%2FFunctions%2F-58641720) |
| [onException](on-exception.md) | [androidJvm]<br>fun [onException](on-exception.md)(exception: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)) |
| [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onFrame](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1950992732%2FFunctions%2F-58641720)(frameTime: [FrameTime](../../../../sceneview/sceneview/io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onPause](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#187777572%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onResume](on-resume.md) | [androidJvm]<br>open override fun [onResume](on-resume.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStart](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#1240777104%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720) | [androidJvm]<br>open override fun [onStop](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#487071706%2FFunctions%2F-58641720)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview.ar.scene/-plane-renderer/index.md#279805282%2FFunctions%2F-58641720)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [showCameraPermissionSettings](show-camera-permission-settings.md) | [androidJvm]<br>fun [showCameraPermissionSettings](show-camera-permission-settings.md)(activity: [Activity](https://developer.android.com/reference/kotlin/android/app/Activity.html)) |

## Properties

| Name | Summary |
|---|---|
| [appSettingsLauncher](app-settings-launcher.md) | [androidJvm]<br>lateinit var [appSettingsLauncher](app-settings-launcher.md): [ActivityResultLauncher](https://developer.android.com/reference/kotlin/androidx/activity/result/ActivityResultLauncher.html)&lt;[Intent](https://developer.android.com/reference/kotlin/android/content/Intent.html)&gt; |
| [cameraPermissionLauncher](camera-permission-launcher.md) | [androidJvm]<br>lateinit var [cameraPermissionLauncher](camera-permission-launcher.md): [ActivityResultLauncher](https://developer.android.com/reference/kotlin/androidx/activity/result/ActivityResultLauncher.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [checkAvailability](check-availability.md) | [androidJvm]<br>var [checkAvailability](check-availability.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [checkCameraPermission](check-camera-permission.md) | [androidJvm]<br>var [checkCameraPermission](check-camera-permission.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [features](features.md) | [androidJvm]<br>val [features](features.md): () -&gt; [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)&lt;Session.Feature&gt; |
| [lifecycle](lifecycle.md) | [androidJvm]<br>val [lifecycle](lifecycle.md): [ArSceneLifecycle](../-ar-scene-lifecycle/index.md) |
| [onAppSettingsResult](on-app-settings-result.md) | [androidJvm]<br>var [onAppSettingsResult](on-app-settings-result.md): (result: [ActivityResult](https://developer.android.com/reference/kotlin/androidx/activity/result/ActivityResult.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCameraPermissionResult](on-camera-permission-result.md) | [androidJvm]<br>var [onCameraPermissionResult](on-camera-permission-result.md): (isGranted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
