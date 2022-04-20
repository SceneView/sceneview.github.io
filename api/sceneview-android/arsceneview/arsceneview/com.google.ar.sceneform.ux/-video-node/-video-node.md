//[arsceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[VideoNode](index.md)/[VideoNode](-video-node.md)

# VideoNode

[androidJvm]\
open fun [VideoNode](-video-node.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), player: [MediaPlayer](https://developer.android.com/reference/kotlin/android/media/MediaPlayer.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)listener: [VideoNode.Listener](-listener/index.md))

Create a new VideoNode for showing a video from a MediaPlayer instance inside a node on an adjusted plane renderable

## Parameters

androidJvm

| | |
|---|---|
| context | Resources context |
| player | The video media player to render on the plane node |
| listener | Loading listener |

[androidJvm]\
open fun [VideoNode](-video-node.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), player: [MediaPlayer](https://developer.android.com/reference/kotlin/android/media/MediaPlayer.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)chromaKeyColor: [Color](../../../../arsceneview/com.google.ar.sceneform.rendering/-color/index.md), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)listener: [VideoNode.Listener](-listener/index.md))

Create a new VideoNode for showing a video from a MediaPlayer instance inside a node on an adjusted plane renderable with video transparency color set to chromaKeyColor.

## Parameters

androidJvm

| | |
|---|---|
| context | Resources context |
| player | The video media player to render on the plane node |
| chromaKeyColor | Chroma Key color to made the video transparent from |
| listener | Loading listener |

[androidJvm]\
open fun [VideoNode](-video-node.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), lifecycle: [Lifecycle](https://developer.android.com/reference/kotlin/androidx/lifecycle/Lifecycle.html), player: [MediaPlayer](https://developer.android.com/reference/kotlin/android/media/MediaPlayer.html), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)chromaKeyColor: [Color](../../../../arsceneview/com.google.ar.sceneform.rendering/-color/index.md), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)texture: [ExternalTexture](../../../../arsceneview/com.google.ar.sceneform.rendering/-external-texture/index.md), @[Nullable](https://developer.android.com/reference/kotlin/androidx/annotation/Nullable.html)listener: [VideoNode.Listener](-listener/index.md))

Create a new VideoNode for showing a video from a MediaPlayer instance inside a node on your own material renderable and material with video transparency color set to chromaKeyColor

## Parameters

androidJvm

| | |
|---|---|
| context | Resources context |
| player | The video media player to render on the plane node |
| chromaKeyColor | Chroma Key color to made the video transparent from |
| texture | Custom ExternalTexture for using your own renderable and material. Null for default Plane shape renderable. |
| listener | Loading listener |
