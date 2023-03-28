//[sceneview](../../index.md)/[io.github.sceneview.scene](index.md)/[exposureFactor](exposure-factor.md)

# exposureFactor

[androidJvm]\
val Camera.[exposureFactor](exposure-factor.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

###  Computes the exposure normalization factor from the camera's EV100

Calculate a unit-less intensity scale from the actual Filament camera settings

This method is useful when trying to match the lighting of other engines or tools. Many engines/tools use unit-less light intensities, which can be matched by setting the exposure manually.

Filament uses a physically based camera model, with aperture, shutter speed, and sensitivity (ISO). This plays nicely with physical light units (for instance if you measure the sun outside on a sunny day in California you'll get ~110,000 lux and if you set your camera settings to ƒ/16 1/125s ISO 100, exposure will be correct). However many engines use &quot;relative exposure&quot; instead, where exposure is just a float and set to 1.0 by default.

ARCore's light estimation was designed to work with those engines. So we scale light intensities estimations by multiplying the values provided by ARCore by 1.0 / log2((aperture * aperture) / shutterSpeed * 100.0f / sensitivity). This should raise ARCore's values to something that's physically plausible for the chosen exposure.

**Sources:**

- 
   https://github.com/ThomasGorisse/SceneformMaintained/pull/156#issuecomment-911873565
- 
   https://github.com/google/filament/blob/main/filament/src/Exposure.cpp#L46
