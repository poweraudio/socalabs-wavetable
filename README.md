**PowerAudio fork of Wavetable**

This fork of Wavetable has the following changes:

* The plugin is built with [a fork of JUCE] that includes fixes for IBM Power.
* Added installation rules so the plugin can be installed with
  `cmake --install` or `make install`.
* Disabled non-free VST 2 builds by default.
* Enabled building without the VST 2 SDK.
* In the [`lv2-only`] branch, added CMake option `LV2_ONLY` to build the plugin
  only as LV2. (Pass `-DLV2_ONLY=ON` to `cmake` after switching to that
  branch.)

The following changes have since been replicated or superceded upstream:

* Updated dependency [Gin] to include fixes for Power.

[a fork of JUCE]: https://github.com/poweraudio/JUCE
[Gin]: https://github.com/FigBug/Gin
[`lv2-only`]: https://github.com/poweraudio/socalabs-wavetable/tree/lv2-only

---

# Wavetable
Wavetable VST3 / AU / LV2 plugin

![Build](https://github.com/FigBug/Wavetable/workflows/Build/badge.svg)

A 2 oscillator wavetable synth with flexible modulation options.

![Screenshot 1](Screenshots/Screenshot1.png)

[Download](https://github.com/FigBug/Wavetable/releases)

[Product page](https://socalabs.com/synths/Wavetable/)

My synth is BSD licensed, however it depends on JUCE. To use in a commercial application, you must have a JUCE license. Wavetables have their own license. 

Need additional features or help integrating, contact me for consulting services: https://rabiensoftware.com/
