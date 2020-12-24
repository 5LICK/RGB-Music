## RGB Music

Used simple RGB led strip and Arduino to visualize music using the Fourier Transform.

### Based on
Repository: https://github.com/ravyoli314/MusicToLED
Info: https://medium.com/@yolandaluqueh/music-to-led-strip-tutorial-using-fourier-transform-3d203a48fe14

### Description
It is modified version of Arduino sketch and my version of implementation.
![Schematic]Schematic_RGB Music.png "Schematic")

Used Audio Input jack (3.5mm) to read the sound, and PWN pins for RGB channels to sync LED with sound frequencies, which received using FFT algorithm.

Requires the arduinoFFT library: https://github.com/kosme/arduinoFFT

