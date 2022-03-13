//[sceneview](../../../index.md)/[com.google.ar.sceneform.ux](../index.md)/[BaseTransformableNode](index.md)

# BaseTransformableNode

[androidJvm]\
abstract class [BaseTransformableNode](index.md) : [Node](../../io.github.sceneview.node/-node/index.md)

Base class for nodes that can be transformed using gestures from [TransformationSystem](../-transformation-system/index.md).

## Constructors

| | |
|---|---|
| [BaseTransformableNode](-base-transformable-node.md) | [androidJvm]<br>open fun [BaseTransformableNode](-base-transformable-node.md)(transformationSystem: [TransformationSystem](../-transformation-system/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [addChild](index.md#724098565%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [addChild](index.md#724098565%2FFunctions%2F-1571379623)(child: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br>Adds a node as a child of this NodeParent. |
| [callOnHierarchy](index.md#-1309458060%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [callOnHierarchy](index.md#-1309458060%2FFunctions%2F-1571379623)(action: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Traverse the hierarchy and call a method on each node.<br>Traversal is depth first. |
| [clone](../../io.github.sceneview.node/-node/clone.md) | [androidJvm]<br>open fun [clone](../../io.github.sceneview.node/-node/clone.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [copy](index.md#-1167623231%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [copy](index.md#-1167623231%2FFunctions%2F-1571379623)(toNode: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [destroy](../../io.github.sceneview.node/-node/destroy.md) | [androidJvm]<br>open fun [destroy](../../io.github.sceneview.node/-node/destroy.md)()<br> Detach and destroy the node |
| [dispatchTouchEvent](index.md#199698999%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [dispatchTouchEvent](index.md#199698999%2FFunctions%2F-1571379623)(pickHitResult: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), motionEvent: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Calls onTouchEvent if the node is active<br>Used by TouchEventSystem to dispatch touch events. |
| [doOnAttachedToScene](index.md#-1858021101%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [doOnAttachedToScene](index.md#-1858021101%2FFunctions%2F-1571379623)(action: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Performs the given action when the node is attached to the scene.<br>If the node is already attached the action will be performed immediately. |
| [get_children](index.md#75288245%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [get_children](index.md#75288245%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> An immutable list of this parent's children |
| [getAllChildren](index.md#-2004043843%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getAllChildren](index.md#-2004043843%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Traverse the hierarchy<br>Traversal is depth first. |
| [getChildren](index.md#2032575454%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getChildren](index.md#2032575454%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getCollider](index.md#2071160531%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getCollider](index.md#2071160531%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getCollisionShape](index.md#-2086118376%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getCollisionShape](index.md#-2086118376%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The shape to used to detect collisions for this [Node](../../io.github.sceneview.node/-node/index.md)<br>If the shape is not set and renderable is set, then [Renderable.getCollisionShape](../../com.google.ar.sceneform.rendering/-view-renderable/index.md#111252609%2FFunctions%2F-1571379623) is used to detect collisions for this [Node](../../io.github.sceneview.node/-node/index.md). |
| [getHierarchy](index.md#-457392664%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getHierarchy](index.md#-457392664%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Traverse the hierarchy<br>Traversal is depth first. |
| [getOnAttachedToScene](index.md#-447584891%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnAttachedToScene](index.md#-447584891%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Listener for [onAttachToScene](../../io.github.sceneview.node/-node/on-attach-to-scene.md) call |
| [getOnChildAdded](index.md#1135858138%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getOnChildAdded](index.md#1135858138%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getOnChildRemoved](index.md#1161909050%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getOnChildRemoved](index.md#1161909050%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getOnDetachedFromScene](index.md#731878018%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnDetachedFromScene](index.md#731878018%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Listener for [onDetachedFromScene](../../io.github.sceneview.node/-node/on-detached-from-scene.md) call |
| [getOnFrame](index.md#-1305260315%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnFrame](index.md#-1305260315%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Listener for [onFrame](../../io.github.sceneview.node/-node/on-frame.md) call |
| [getOnRenderingChanged](index.md#-479935712%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnRenderingChanged](index.md#-479935712%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Listener for [onRenderingChanged](../../io.github.sceneview.node/-node/on-rendering-changed.md) call |
| [getOnTouched](index.md#-695209964%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnTouched](index.md#-695209964%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Registers a callback to be invoked when this node is tapped.<br>If there is a callback registered, then touch events will not bubble to this node's parent. |
| [getOnTouchEvent](index.md#-2136815955%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnTouchEvent](index.md#-2136815955%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Registers a callback to be invoked when a touch event is dispatched to this node<br>The way that touch events are propagated mirrors the way touches are propagated to Android Views. |
| [getOnTransformChanged](index.md#-231684096%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getOnTransformChanged](index.md#-231684096%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The transformation (position, rotation or scale) of the [Node](../../io.github.sceneview.node/-node/index.md) has changed<br>If node A's position is changed, then that will trigger [onTransformChanged](../../io.github.sceneview.node/-node/on-transform-changed.md) to be called for all of it's descendants. |
| [getParent](index.md#2038999389%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getParent](index.md#2038999389%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Changes the parent node of this node<br>If set to null, this node will be detached ([removeChild](../../../../sceneview/io.github.sceneview.node/-node/remove-child.md)) from its parent. |
| [getParentNode](index.md#-1481703045%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getParentNode](index.md#-1481703045%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The [Node](../../io.github.sceneview.node/-node/index.md) parent if the parent extends [Node](../../io.github.sceneview.node/-node/index.md)<br>Returns null if the parent is not a [Node](../../io.github.sceneview.node/-node/index.md). |
| [getPosition](index.md#537443134%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getPosition](index.md#537443134%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node position<br>The node's position locates it within the coordinate system of its parent. |
| [getQuaternion](index.md#-1020199831%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getQuaternion](index.md#-1020199831%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br>TODO: Doc |
| [getRotation](index.md#725327497%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getRotation](index.md#725327497%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node orientation in Euler Angles Degrees per axis.<br>[0..360]The three-component rotation vector specifies the direction of the rotation axis in degrees. |
| [getScale](index.md#1687444841%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getScale](index.md#1687444841%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node scale on each axis.<br>-     reduce size: scale < 1.0f -     same size: scale = 1.0f -     increase size: scale 1.0f |
| [getSceneViewInternal](../../io.github.sceneview.node/-node/get-scene-view-internal.md) | [androidJvm]<br>fun [getSceneViewInternal](../../io.github.sceneview.node/-node/get-scene-view-internal.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getShouldBeRendered$module](index.md#961684622%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getShouldBeRendered$module](index.md#961684622%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The active status<br>A node is considered active if it meets ALL of the following conditions:<br>-     The node is part of a scene. -     the node's parent is active. -     The node is enabled.<br>An active Node has the following behavior:<br>-     The node's [onFrame](../../io.github.sceneview.node/-node/on-frame.md) function will be called every frame. -     The node's [Renderable](../../com.google.ar.sceneform.rendering/-renderable/index.md) will be rendered. -     The node's [collisionShape](../../io.github.sceneview.node/-node/collision-shape.md) will be checked in calls to Scene.hitTest. -     The node's [onTouchEvent](../../io.github.sceneview.node/-node/on-touch-event.md) function will be called when the node is touched. |
| [getSmoothRotationThreshold](index.md#1309891668%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getSmoothRotationThreshold](index.md#1309891668%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The smooth rotation minimum change limit<br>This is used to avoid very near rotations smooth modifications. |
| [getSmoothSpeed](index.md#1165855194%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [getSmoothSpeed](index.md#1165855194%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The smooth position, rotation and scale speed<br>Expressed in units per seconds. |
| [getTransform](index.md#-551060857%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getTransform](index.md#-551060857%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getTransformationMatrix](../../com.google.ar.sceneform.common/-transform-provider/get-transformation-matrix.md) | [androidJvm]<br>abstract fun [getTransformationMatrix](../../com.google.ar.sceneform.common/-transform-provider/get-transformation-matrix.md)(): [Matrix](../../com.google.ar.sceneform.math/-matrix/index.md)<br>open fun [getTransformationMatrix](../../io.github.sceneview.node/-node/get-transformation-matrix.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getTransformationMatrixInverted](index.md#696826600%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getTransformationMatrixInverted](index.md#696826600%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [getWorldPosition](index.md#372481784%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getWorldPosition](index.md#372481784%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node world-space position<br>The world position of this node (i.e. |
| [getWorldRotation](index.md#560366147%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getWorldRotation](index.md#560366147%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node world-space rotation<br>The world rotation of this node (i.e. |
| [getWorldScale](index.md#-1543986193%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getWorldScale](index.md#-1543986193%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node world-space scale<br>The world scale of this node (i.e. |
| [getWorldTransform](index.md#-1369895411%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [getWorldTransform](index.md#-1369895411%2FFunctions%2F-1571379623)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [isAttached](../../io.github.sceneview.node/-node/is-attached.md) | [androidJvm]<br>fun [isAttached](../../io.github.sceneview.node/-node/is-attached.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [isDescendantOf](index.md#2048923096%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [isDescendantOf](index.md#2048923096%2FFunctions%2F-1571379623)(ancestor: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Checks whether the given node parent is an ancestor of this node recursively<br>Return true if the node is an ancestor of this node |
| [isFocusable](../../io.github.sceneview.node/-node/is-focusable.md) | [androidJvm]<br>fun [isFocusable](../../io.github.sceneview.node/-node/is-focusable.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The node can be focused within the [com.google.ar.sceneform.collision.CollisionSystem](../../com.google.ar.sceneform.collision/-collision-system/index.md)<br>when a touch event happenedtrue if the node can be selected |
| [isRendered](../../io.github.sceneview.node/-node/is-rendered.md) | [androidJvm]<br>open fun [isRendered](../../io.github.sceneview.node/-node/is-rendered.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html) |
| [isSelected](is-selected.md) | [androidJvm]<br>open fun [isSelected](is-selected.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if this node is currently selected by the TransformationSystem. |
| [isTransforming](is-transforming.md) | [androidJvm]<br>open fun [isTransforming](is-transforming.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns true if any of the transformation controllers are actively transforming this node. |
| [isVisible](../../io.github.sceneview.node/-node/is-visible.md) | [androidJvm]<br>open fun [isVisible](../../io.github.sceneview.node/-node/is-visible.md)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> The visible state of this node.<br>Note that a Node may be enabled but still inactive if it isn't part of the scene or if its parent is inactive. |
| [onAttachToScene](index.md#246391689%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onAttachToScene](index.md#246391689%2FFunctions%2F-1571379623)(sceneView: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onChildAdded](index.md#-845627021%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onChildAdded](index.md#-845627021%2FFunctions%2F-1571379623)(child: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onChildRemoved](index.md#-1846922541%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onChildRemoved](index.md#-1846922541%2FFunctions%2F-1571379623)(child: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onCreate](index.md#139941652%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onCreate](index.md#139941652%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onDestroy](index.md#1057561704%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onDestroy](index.md#1057561704%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html))<br>open fun [onDestroy](index.md#-1984481701%2FFunctions%2F-1571379623)(owner: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onDetachFromScene](index.md#-1410017594%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onDetachFromScene](index.md#-1410017594%2FFunctions%2F-1571379623)(sceneView: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onFrame](index.md#1537984904%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onFrame](index.md#1537984904%2FFunctions%2F-1571379623)(frameTime: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [onPause](index.md#187777572%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onPause](index.md#187777572%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onRenderingChanged](index.md#-49956369%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onRenderingChanged](index.md#-49956369%2FFunctions%2F-1571379623)(isRendering: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Handles when this node becomes rendered (displayed) or not<br>A Node is rendered if it's visible, part of a scene, and its parent is rendered. |
| [onResume](index.md#-1807945979%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onResume](index.md#-1807945979%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStart](index.md#1240777104%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onStart](index.md#1240777104%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onStop](index.md#487071706%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onStop](index.md#487071706%2FFunctions%2F-1571379623)(owner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html)) |
| [onSurfaceChanged](index.md#-1329673342%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [onSurfaceChanged](index.md#-1329673342%2FFunctions%2F-1571379623)(width: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), height: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br>Records a change in surface dimensions. |
| [onTap](on-tap.md) | [androidJvm]<br>open fun [onTap](on-tap.md)(pickHitResult: [PickHitResult](../../com.google.ar.sceneform/-pick-hit-result/index.md), motionEvent: [MotionEvent](https://developer.android.com/reference/kotlin/android/view/MotionEvent.html)) |
| [onTouchEvent](index.md#-294379492%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [onTouchEvent](index.md#-294379492%2FFunctions%2F-1571379623)(pickHitResult: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), motionEvent: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br> Handles when this node is touched<br>Override to perform any logic that should occur when this node is touched. |
| [onTransformChanged](../../io.github.sceneview.node/-node/on-transform-changed.md) | [androidJvm]<br>open fun [onTransformChanged](../../io.github.sceneview.node/-node/on-transform-changed.md)()<br> The transformation (position, rotation or scale) of the [Node](../../io.github.sceneview.node/-node/index.md) has changed<br>If node A's position is changed, then that will trigger [onTransformChanged](../../io.github.sceneview.node/-node/on-transform-changed.md) to be called for all of it's descendants. |
| [removeChild](index.md#-1208387756%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [removeChild](index.md#-1208387756%2FFunctions%2F-1571379623)(child: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br>Removes a node from the children of this NodeParent. |
| [scale](index.md#65728652%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [scale](index.md#65728652%2FFunctions%2F-1571379623)(scale: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The node scale<br>-     reduce size: scale < 1.0f -     same size: scale = 1.0f -     increase size: scale 1.0f |
| [select](select.md) | [androidJvm]<br>open fun [select](select.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Sets this as the selected node in the TransformationSystem if there is no currently selected node or if the currently selected node is not actively being transformed. |
| [set_children](index.md#1985729370%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [set_children](index.md#1985729370%2FFunctions%2F-1571379623)(_children: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> An immutable list of this parent's children |
| [setChildren](index.md#-1472581013%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setChildren](index.md#-1472581013%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [setCollisionShape](index.md#1250203301%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setCollisionShape](index.md#1250203301%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The shape to used to detect collisions for this [Node](../../io.github.sceneview.node/-node/index.md)<br>If the shape is not set and renderable is set, then [Renderable.getCollisionShape](../../com.google.ar.sceneform.rendering/-view-renderable/index.md#111252609%2FFunctions%2F-1571379623) is used to detect collisions for this [Node](../../io.github.sceneview.node/-node/index.md). |
| [setFocusable](index.md#-1447825114%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setFocusable](index.md#-1447825114%2FFunctions%2F-1571379623)(isFocusable: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The node can be focused within the [com.google.ar.sceneform.collision.CollisionSystem](../../com.google.ar.sceneform.collision/-collision-system/index.md)<br>when a touch event happenedtrue if the node can be selected |
| [setOnTouched](index.md#-583979719%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setOnTouched](index.md#-583979719%2FFunctions%2F-1571379623)(onTouched: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Registers a callback to be invoked when this node is tapped.<br>If there is a callback registered, then touch events will not bubble to this node's parent. |
| [setOnTouchEvent](index.md#-1981285446%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setOnTouchEvent](index.md#-1981285446%2FFunctions%2F-1571379623)(onTouchEvent: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Registers a callback to be invoked when a touch event is dispatched to this node<br>The way that touch events are propagated mirrors the way touches are propagated to Android Views. |
| [setParent](index.md#1871146346%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setParent](index.md#1871146346%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Changes the parent node of this node<br>If set to null, this node will be detached ([removeChild](../../../../sceneview/io.github.sceneview.node/-node/remove-child.md)) from its parent. |
| [setPosition](index.md#1468111307%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setPosition](index.md#1468111307%2FFunctions%2F-1571379623)(position: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The node position<br>The node's position locates it within the coordinate system of its parent. |
| [setQuaternion](index.md#5668982%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setQuaternion](index.md#5668982%2FFunctions%2F-1571379623)(quaternion: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br>TODO: Doc |
| [setRendered$module](index.md#1824835901%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setRendered$module](index.md#1824835901%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [setRotation](index.md#-55844970%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setRotation](index.md#-55844970%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The node orientation in Euler Angles Degrees per axis.<br>[0..360]The three-component rotation vector specifies the direction of the rotation axis in degrees. |
| [setScale](index.md#574672398%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setScale](index.md#574672398%2FFunctions%2F-1571379623)(scale: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The node scale on each axis.<br>-     reduce size: scale < 1.0f -     same size: scale = 1.0f -     increase size: scale 1.0f |
| [setSmoothRotationThreshold](index.md#689337465%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setSmoothRotationThreshold](index.md#689337465%2FFunctions%2F-1571379623)(smoothRotationThreshold: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The smooth rotation minimum change limit<br>This is used to avoid very near rotations smooth modifications. |
| [setSmoothSpeed](index.md#-1407213313%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [setSmoothSpeed](index.md#-1407213313%2FFunctions%2F-1571379623)(smoothSpeed: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The smooth position, rotation and scale speed<br>Expressed in units per seconds. |
| [setTransform](index.md#1632126508%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setTransform](index.md#1632126508%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)) |
| [setVisible](index.md#751202150%2FFunctions%2F-1571379623) | [androidJvm]<br>open fun [setVisible](index.md#751202150%2FFunctions%2F-1571379623)(value: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> The visible state of this node.<br>Note that a Node may be enabled but still inactive if it isn't part of the scene or if its parent is inactive. |
| [smooth](index.md#25919984%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [smooth](index.md#25919984%2FFunctions%2F-1571379623)(position: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), quaternion: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), rotation: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), speed: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Smooth move, rotate and scale at a specified speed |
| [transform](index.md#1390710830%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [transform](index.md#1390710830%2FFunctions%2F-1571379623)(position: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), quaternion: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), rotation: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html), scale: [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html))<br> Change the node transform |
| [updateVisibility$module](index.md#-254763992%2FFunctions%2F-1571379623) | [androidJvm]<br>fun [updateVisibility$module](index.md#-254763992%2FFunctions%2F-1571379623)() |

## Properties

| Name | Summary |
|---|---|
| [transformationSystem](transformation-system.md) | [androidJvm]<br>private val [transformationSystem](transformation-system.md): [TransformationSystem](../-transformation-system/index.md) |