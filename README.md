<!-- mdformat off(b/169948621#comment2) -->

# Micro Speech Example

This example shows how to run a 20 kB model that can recognize 2 keywords,
"yes" and "no", from speech data.

The application listens to its surroundings with a microphone and indicates
when it has detected a word by lighting an LED or displaying data on a
screen, depending on the capabilities of the device.

![Animation on Arduino](../../docs/animation_on_arduino.gif)

The code has a small footprint (for example, around 166 kilobytes on a Cortex
M4) and only uses about 54 kilobytes of additional RAM for working memory.

# Magic Wand

Magic Wand example for TensorFlow Lite Micro on the Arduino Nano 33 BLE Sense.
