//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Light](../index.md)/[Builder](index.md)/[setInnerConeAngle](set-inner-cone-angle.md)

# setInnerConeAngle

[androidJvm]\
open fun [setInnerConeAngle](set-inner-cone-angle.md)(coneInner: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Light.Builder](index.md)

Spotlights shine light in a cone, this value determines the size of the inner part of the cone. The intensity is interpolated between the inner and outer cone angles - meaning if they are the same than the cone is perfectly sharp. Generally you will want the inner cone to be smaller than the outer cone to avoid aliasing.

## Parameters

androidJvm

| | |
|---|---|
| coneInner | inner cone angle in radians, default is 0.5 |
