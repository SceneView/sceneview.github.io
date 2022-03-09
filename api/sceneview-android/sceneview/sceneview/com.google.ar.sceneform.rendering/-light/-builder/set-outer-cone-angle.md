//[sceneview](../../../../index.md)/[com.google.ar.sceneform.rendering](../../index.md)/[Light](../index.md)/[Builder](index.md)/[setOuterConeAngle](set-outer-cone-angle.md)

# setOuterConeAngle

[androidJvm]\
open fun [setOuterConeAngle](set-outer-cone-angle.md)(coneOuter: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): [Light.Builder](index.md)

Spotlights shine light in a cone, this value determines the size of the outer part of the cone. The intensity is interpolated between the inner and outer cone angles - meaning if they are the same than the cone is perfectly sharp. Generally you will want the inner cone to be smaller than the outer cone to avoid aliasing.

## Parameters

androidJvm

| | |
|---|---|
| coneOuter | outer cone angle in radians, default is 0.6 |
