# Ħemda Studio

**Open it: https://robert1994.github.io/-emda/**

Ħemda is a standalone ambient synth designed by Robert Farrugia. This repository publishes its PC app:

- **Emulator**: the real Ħemda firmware (sound engine and screen) running in your browser. Play it with the mouse, the computer keyboard or a MIDI keyboard.
- **Manager**: connect the synth over USB-C (Chrome or Edge) to edit every parameter, presets, button and knob jobs, settings, and to read the device log.
- **Firmware install**: the firmware file that comes with your Ħemda installs in about 20 seconds, read back and checked.

Firmware 1.2.0 adds **Bluetooth MIDI**: the synth pairs as “Ħemda XXXX” with an iPad, Mac, PC or Android phone (Menu > Bluetooth MIDI to turn it off).
Firmware 1.4.0 adds an FX + LINES page set (hold PLAY: generation loss, tape echo, shimmer reverb, line in / out routing), nine analog instruments made from Blofeld sounds (Angels Cry, Heaven, BloChoir, Deepspace 9, Tines&Bars, ArcoStrings, Poly Flutes, Vangelibells, Xells E.Piano), MIDI learn (hold LATCH), MIDI maps for common keyboards, encoder-push options, undo, hold-to-save presets and screen dimming.

Firmware 1.3.0 and later can also be installed **over Bluetooth** from Hemda Studio (Chrome or Edge, or Chrome on Android): the synth asks you to push encoder 1 first.

| File | What |
|---|---|
| `studio/index.html` | Hemda Studio (one self-contained page, also works saved to disk) |

© Robert Farrugia. Hemda Studio bundles [esptool-js](https://github.com/espressif/esptool-js) (Apache-2.0) for flashing.
