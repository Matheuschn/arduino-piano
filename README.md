# Arduino Piano/Keyboard
A piano/keyboard made with an Arduino, a passive buzzer and capacitive-touch sensors for the course Laboratório de Transdutores at UFSC.

## How it works?
The keys are capacitive-touch sensors made of strips of aluminum foil, connected to the Arduino with jumpers.

The code uses a third-party library (embedded on the file itself) called "readCapacitivePin", which translates the capacitance present on each pin to a numeric value. If the value is higher than the threshold, the buzzer sounds with the associated frequency. When a finger touches the key, the capacitance changes, triggering the Arduino to play the sound.

## In action

Present on this repo is a PDF file used for the presentation of the project, and [here](https://youtu.be/3rInVPDhtQo) is a link to a YouTube video showing me playing some tunes and explaining more about the schematics.
