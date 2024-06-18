# tiltlights

This is a hex file for the BBC Microbit to create a bicycle indicator system.  The idea is that you can put LED arrays on your helmet or bicycle, and then when you tilt your head to the sude, it indicates in that direction.
If you give a quick nod, it will turn off.
As the microbit doesn't tilt around the Z-axis, I had to hack the numbers for the Y axis, which seems to work ok.

Future improvements:

- I'd like to add acceleration to the equation, so you need to quickly tilt to avoid false indications
- There should be a sound, or visual sensor to the wearer knows the indication status
- There's a bug where if you do it too quickly, it indicates to the wrong side!


[![Watch the video](https://img.youtube.com/vi/XrYGqzNvnz4/maxresdefault.jpg)](https://youtu.be/XrYGqzNvnz4)
