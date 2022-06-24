//[sceneview](../../../index.md)/[io.github.sceneview.node](../index.md)/[Node](index.md)

# Node

[androidJvm]\
open class [Node](index.md) : [NodeParent](../-node-parent/index.md), [TransformProvider](../../com.google.ar.sceneform.common/-transform-provider/index.md), [SceneLifecycleObserver](../../io.github.sceneview/-scene-lifecycle-observer/index.md)

###  A Node represents a transformation within the scene graph's hierarchy.

It can contain a renderable for the rendering engine to render.

Each node can have an arbitrary number of child nodes and one parent. The parent may be another node, or the scene.

------- +y ----- -z

---------|----/----

---------|--/------

-x - - - 0 - - - +x

------/--|---------

----/----|---------

+z ---- -y --------

## Constructors

| | |
|---|---|
| [Node](-node.md) | [androidJvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [Node](-node.md)(position: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = DEFAULT_POSITION, rotation: [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623) = DEFAULT_ROTATION, scale: [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623) = DEFAULT_SCALE) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addChild](../-node-parent/add-child.md) | [androidJvm]<br>@[UiThread](https://developer.android.com/reference/kotlin/androidx/annotation/UiThread.html)<br>open fun [addChild](../-node-parent/add-child.md)(child: [Node](index.md)): [Node](index.md)<br>Adds a node as a child of this NodeParent. If the node already has a parent, it is removed from its old parent. If the node is already a direct child of this NodeParent, no change is made. |
| [callOnHierarchy](../-node-parent/call-on-hierarchy.md) | [androidJvm]<br>open fun [callOnHierarchy](../-node-parent/call-on-hierarchy.md)(action: ([Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [clone](clone.md) | [androidJvm]<br>open fun [clone](clone.md)(): [Node](index.md) |
| [copy](copy.md) | [androidJvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>open fun [copy](copy.md)(toNode: [Node](index.md) = Node()): [Node](index.md) |
| [destroy](destroy.md) | [androidJvm]<br>open fun [destroy](destroy.md)() |
| [doOnAttachedToScene](do-on-attached-to-scene.md) | [androidJvm]<br>fun [doOnAttachedToScene](do-on-attached-to-scene.md)(action: (scene: [SceneView](../../io.github.sceneview/-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>If the node is already attached the action will be performed immediately. Else this action will be invoked the first time the scene is attached. |
| [firstEnclosingNode](first-enclosing-node.md) | [androidJvm]<br>inline fun &lt;[T](first-enclosing-node.md) : [Node](index.md)&gt; [firstEnclosingNode](first-enclosing-node.md)(): [T](first-enclosing-node.md)?<br>The node can be: |
| [getSceneViewInternal](get-scene-view-internal.md) | [androidJvm]<br>fun [getSceneViewInternal](get-scene-view-internal.md)(): [SceneView](../../io.github.sceneview/-scene-view/index.md)? |
| [getTransformationMatrix](get-transformation-matrix.md) | [androidJvm]<br>open override fun [getTransformationMatrix](get-transformation-matrix.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md) |
| [isDescendantOf](is-descendant-of.md) | [androidJvm]<br>fun [isDescendantOf](is-descendant-of.md)(ancestor: [NodeParent](../-node-parent/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Return true if the node is an ancestor of this node |
| [onAttachToScene](on-attach-to-scene.md) | [androidJvm]<br>open fun [onAttachToScene](on-attach-to-scene.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md)) |
| [onChildAdded](on-child-added.md) | [androidJvm]<br>open override fun [onChildAdded](on-child-added.md)(child: [Node](index.md)) |
| [onChildRemoved](on-child-removed.md) | [androidJvm]<br>open override fun [onChildRemoved](on-child-removed.md)(child: [Node](index.md)) |
| [onCreate](../-view-node/index.md#139941652%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onCreate](../-view-node/index.md#139941652%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](on-destroy.md) | [androidJvm]<br>open override fun [onDestroy](on-destroy.md)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDetachFromScene](on-detach-from-scene.md) | [androidJvm]<br>open fun [onDetachFromScene](on-detach-from-scene.md)(sceneView: [SceneView](../../io.github.sceneview/-scene-view/index.md)) |
| [onFrame](on-frame.md) | [androidJvm]<br>open override fun [onFrame](on-frame.md)(frameTime: [FrameTime](../../io.github.sceneview.utils/-frame-time/index.md)) |
| [onPause](../-view-node/index.md#187777572%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onPause](../-view-node/index.md#187777572%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onRenderingChanged](on-rendering-changed.md) | [androidJvm]<br>open fun [onRenderingChanged](on-rendering-changed.md)(isRendering: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>A Node is rendered if it's visible, part of a scene, and its parent is rendered. Override to perform any setup that needs to occur when the node is active or not. |
| [onResume](../-view-node/index.md#-1807945979%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onResume](../-view-node/index.md#-1807945979%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSmoothEnd](on-smooth-end.md) | [androidJvm]<br>open fun [onSmoothEnd](on-smooth-end.md)() |
| [onStart](../-view-node/index.md#1240777104%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStart](../-view-node/index.md#1240777104%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](../-view-node/index.md#487071706%2FFunctions%2F-1571379623) | [androidJvm]<br>open override fun [onStop](../-view-node/index.md#487071706%2FFunctions%2F-1571379623)(@[NonNull](https://developer.android.com/reference/kotlin/androidx/annotation/NonNull.html)p0: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md) | [androidJvm]<br>open fun [onSurfaceChanged](../../io.github.sceneview/-scene-lifecycle-observer/on-surface-changed.md)(width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Records a change in surface dimensions. |
| [onTap](on-tap.md) | [androidJvm]<br>open fun [onTap](on-tap.md)(renderable: [Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html))<br>Calls the onTap listener if it is available and passes the tap to the parent node. |
| [onTransformChanged](on-transform-changed.md) | [androidJvm]<br>open fun [onTransformChanged](on-transform-changed.md)()<br>If node A's position is changed, then that will trigger [onTransformChanged](on-transform-changed.md) to be called for all of it's descendants. |
| [removeChild](../-node-parent/remove-child.md) | [androidJvm]<br>open fun [removeChild](../-node-parent/remove-child.md)(child: [Node](index.md)): [Node](index.md)<br>Removes a node from the children of this NodeParent. If the node is not a direct child of this NodeParent, no change is made. |
| [scale](scale.md) | [androidJvm]<br>fun [scale](scale.md)(scale: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)) |
| [smooth](smooth.md) | [androidJvm]<br>fun [smooth](smooth.md)(transform: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623), speed: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = this.smoothSpeed)<br>fun [smooth](smooth.md)(position: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = this.position, quaternion: [Quaternion](../../dev.romainguy.kotlin.math/-quaternion/index.md) = this.quaternion, rotation: [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623) = this.rotation, scale: [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623) = this.scale, speed: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = this.smoothSpeed) |
| [transform](transform.md) | [androidJvm]<br>fun [transform](transform.md)(position: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623) = this.position, quaternion: [Quaternion](../../dev.romainguy.kotlin.math/-quaternion/index.md) = this.quaternion, rotation: [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623) = this.rotation, scale: [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623) = this.scale) |
| [updateVisibility](update-visibility.md) | [androidJvm]<br>fun [updateVisibility](update-visibility.md)() |

## Properties

| Name | Summary |
|---|---|
| [_children](_children.md) | [androidJvm]<br>open override var [_children](_children.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](index.md)&gt; |
| [allChildren](../-node-parent/all-children.md) | [androidJvm]<br>open val [allChildren](../-node-parent/all-children.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](index.md)&gt;<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [children](../-node-parent/children.md) | [androidJvm]<br>open var [children](../-node-parent/children.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](index.md)&gt; |
| [collider](collider.md) | [androidJvm]<br>var [collider](collider.md): [Collider](../../com.google.ar.sceneform.collision/-collider/index.md)? = null |
| [collisionShape](collision-shape.md) | [androidJvm]<br>var [collisionShape](collision-shape.md): [CollisionShape](../../com.google.ar.sceneform.collision/-collision-shape/index.md)? = null<br>If the shape is not set and renderable is set, then Renderable.getCollisionShape is used to detect collisions for this [Node](index.md). |
| [hierarchy](../-node-parent/hierarchy.md) | [androidJvm]<br>open val [hierarchy](../-node-parent/hierarchy.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Node](index.md)&gt;<br>Traversal is depth first. If this NodeParent is a Node, traversal starts with this NodeParent, otherwise traversal starts with its children. |
| [isAttached](is-attached.md) | [androidJvm]<br>val [isAttached](is-attached.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFocusable](is-focusable.md) | [androidJvm]<br>var [isFocusable](is-focusable.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>when a touch event happened |
| [isRendered](is-rendered.md) | [androidJvm]<br>open var [isRendered](is-rendered.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [isVisible](is-visible.md) | [androidJvm]<br>open var [isVisible](is-visible.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true<br>Note that a Node may be enabled but still inactive if it isn't part of the scene or if its parent is inactive. |
| [name](name.md) | [androidJvm]<br>var [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [onAttachedToScene](on-attached-to-scene.md) | [androidJvm]<br>val [onAttachedToScene](on-attached-to-scene.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(scene: [SceneView](../../io.github.sceneview/-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt; |
| [onChildAdded](../-node-parent/on-child-added.md) | [androidJvm]<br>open val [onChildAdded](../-node-parent/on-child-added.md): ([Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [onChildRemoved](../-node-parent/on-child-removed.md) | [androidJvm]<br>open val [onChildRemoved](../-node-parent/on-child-removed.md): ([Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [onDetachedFromScene](on-detached-from-scene.md) | [androidJvm]<br>val [onDetachedFromScene](on-detached-from-scene.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(scene: [SceneView](../../io.github.sceneview/-scene-view/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt; |
| [onFrame](on-frame.md) | [androidJvm]<br>val [onFrame](on-frame.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(frameTime: [FrameTime](../../io.github.sceneview.utils/-frame-time/index.md), node: [Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt; |
| [onRenderingChanged](on-rendering-changed.md) | [androidJvm]<br>val [onRenderingChanged](on-rendering-changed.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(node: [Node](index.md), isRendering: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt; |
| [onSmoothEnd](on-smooth-end.md) | [androidJvm]<br>var [onSmoothEnd](on-smooth-end.md): (node: [Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null |
| [onTap](on-tap.md) | [androidJvm]<br>var [onTap](on-tap.md): ([Renderable](../../io.github.sceneview.renderable/index.md#286838466%2FClasslikes%2F-1571379623), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? = null<br>Only nodes with renderables or their parent nodes can be tapped since Filament picking is used to find a touched node. The ID of the Filament renderable can be used to determine what part of a model is tapped. |
| [onTransformChanged](on-transform-changed.md) | [androidJvm]<br>val [onTransformChanged](on-transform-changed.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;(node: [Node](index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)&gt;<br>If node A's position is changed, then that will trigger [onTransformChanged](on-transform-changed.md) to be called for all of it's descendants. |
| [parent](parent.md) | [androidJvm]<br>var [parent](parent.md): [NodeParent](../-node-parent/index.md)? = null<br>If set to null, this node will be detached ([removeChild](../../../../sceneview/io.github.sceneview.node/-node/remove-child.md)) from its parent. |
| [parentNode](parent-node.md) | [androidJvm]<br>val [parentNode](parent-node.md): [Node](index.md)?<br>Returns null if the parent is not a [Node](index.md). = Returns null if the parent is a [SceneView](../../io.github.sceneview/-scene-view/index.md) |
| [position](position.md) | [androidJvm]<br>var [position](position.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)<br>Default is Position(x = 0.0f, y = 0.0f, z = 0.0f), indicating that the node is placed at the origin of the parent node's coordinate system. |
| [quaternion](quaternion.md) | [androidJvm]<br>var [quaternion](quaternion.md): [Quaternion](../../dev.romainguy.kotlin.math/-quaternion/index.md)<br>TODO: Doc |
| [rotation](rotation.md) | [androidJvm]<br>var [rotation](rotation.md): [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623)<br>The three-component rotation vector specifies the direction of the rotation axis in degrees. Rotation is applied relative to the node's origin property. |
| [scale](scale.md) | [androidJvm]<br>var [scale](scale.md): [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623)<br>Reduce (scale &lt; 1.0f) / Increase (scale &gt; 1.0f) |
| [shouldBeRendered](should-be-rendered.md) | [androidJvm]<br>open val [shouldBeRendered](should-be-rendered.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>A node is considered active if it meets ALL of the following conditions: |
| [smoothRotationThreshold](smooth-rotation-threshold.md) | [androidJvm]<br>var [smoothRotationThreshold](smooth-rotation-threshold.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)<br>This is used to avoid very near rotations smooth modifications. It prevents the rotation to appear too quick if the ranges are too close and uses linearly interpolation for upper dot products. |
| [smoothSpeed](smooth-speed.md) | [androidJvm]<br>var [smoothSpeed](smooth-speed.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 5.0f<br>Expressed in units per seconds. On an AR context, 1 unit = 1 meter. So, for position, this value defines the meters per seconds for a node move. This value is used by [smooth](smooth.md) |
| [transform](transform.md) | [androidJvm]<br>open var [transform](transform.md): [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-1571379623) |
| [transformationMatrixInverted](transformation-matrix-inverted.md) | [androidJvm]<br>open val [transformationMatrixInverted](transformation-matrix-inverted.md): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md) |
| [worldPosition](world-position.md) | [androidJvm]<br>open var [worldPosition](world-position.md): [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-1571379623)<br>The world position of this node (i.e. relative to the [SceneView](../../io.github.sceneview/-scene-view/index.md)). This is the composition of this component's local position with its parent's world position. |
| [worldQuaternion](world-quaternion.md) | [androidJvm]<br>open var [worldQuaternion](world-quaternion.md): [Quaternion](../../dev.romainguy.kotlin.math/-quaternion/index.md)<br>The world quaternion of this node (i.e. relative to the [SceneView](../../io.github.sceneview/-scene-view/index.md)). This is the composition of this component's local quaternion with its parent's world quaternion. |
| [worldRotation](world-rotation.md) | [androidJvm]<br>open var [worldRotation](world-rotation.md): [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-1571379623)<br>The world rotation of this node (i.e. relative to the [SceneView](../../io.github.sceneview/-scene-view/index.md)). This is the composition of this component's local rotation with its parent's world rotation. |
| [worldScale](world-scale.md) | [androidJvm]<br>open var [worldScale](world-scale.md): [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-1571379623)<br>The world scale of this node (i.e. relative to the [SceneView](../../io.github.sceneview/-scene-view/index.md)). This is the composition of this component's local scale with its parent's world scale. |
| [worldTransform](world-transform.md) | [androidJvm]<br>open val [worldTransform](world-transform.md): [Mat4](../../dev.romainguy.kotlin.math/-mat4/index.md) |

## Inheritors

| Name |
|---|
| [Camera](../../com.google.ar.sceneform/-camera/index.md) |
| [LightNode](../-light-node/index.md) |
| [ModelNode](../-model-node/index.md) |
| [ViewNode](../-view-node/index.md) |
