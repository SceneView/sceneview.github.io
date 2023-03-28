//[sceneview_1_0_0](../../../index.md)/[io.github.sceneview.animation](../index.md)/[TransformAnimator](index.md)

# TransformAnimator

[androidJvm]\
object [TransformAnimator](index.md)

## Types

| Name | Summary |
|---|---|
| [Float3Evaluator](-float3-evaluator/index.md) | [androidJvm]<br>class [Float3Evaluator](-float3-evaluator/index.md) : [TypeEvaluator](https://developer.android.com/reference/kotlin/android/animation/TypeEvaluator.html)&lt;[Float3](../../../../sceneview/sceneview/dev.romainguy.kotlin.math/-float3/index.md)&gt; |
| [QuaternionEvaluator](-quaternion-evaluator/index.md) | [androidJvm]<br>class [QuaternionEvaluator](-quaternion-evaluator/index.md) : [TypeEvaluator](https://developer.android.com/reference/kotlin/android/animation/TypeEvaluator.html)&lt;[Quaternion](../../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md)&gt; |
| [TransformEvaluator](-transform-evaluator/index.md) | [androidJvm]<br>class [TransformEvaluator](-transform-evaluator/index.md) : [TypeEvaluator](https://developer.android.com/reference/kotlin/android/animation/TypeEvaluator.html)&lt;[Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187)&gt; |

## Functions

| Name | Summary |
|---|---|
| [ofPosition](of-position.md) | [androidJvm]<br>fun [ofPosition](of-position.md)(transformable: [TransformComponent](../../io.github.sceneview.components/-transform-component/index.md), vararg positions: [Position](../../io.github.sceneview.math/index.md#945960193%2FClasslikes%2F-602047187)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |
| [ofQuaternion](of-quaternion.md) | [androidJvm]<br>fun [ofQuaternion](of-quaternion.md)(transformable: [TransformComponent](../../io.github.sceneview.components/-transform-component/index.md), vararg quaternions: [Quaternion](../../../../sceneview/sceneview/dev.romainguy.kotlin.math/-quaternion/index.md)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |
| [ofRotation](of-rotation.md) | [androidJvm]<br>fun [ofRotation](of-rotation.md)(transformable: [TransformComponent](../../io.github.sceneview.components/-transform-component/index.md), vararg rotations: [Rotation](../../io.github.sceneview.math/index.md#1133844556%2FClasslikes%2F-602047187)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |
| [ofScale](of-scale.md) | [androidJvm]<br>fun [ofScale](of-scale.md)(transformable: [TransformComponent](../../io.github.sceneview.components/-transform-component/index.md), vararg scales: [Scale](../../io.github.sceneview.math/index.md#2055938798%2FClasslikes%2F-602047187)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |
| [ofTransform](of-transform.md) | [androidJvm]<br>fun [ofTransform](of-transform.md)(transformable: [TransformComponent](../../io.github.sceneview.components/-transform-component/index.md), vararg transforms: [Transform](../../io.github.sceneview.math/index.md#1875660684%2FClasslikes%2F-602047187)): [ObjectAnimator](https://developer.android.com/reference/kotlin/android/animation/ObjectAnimator.html) |
