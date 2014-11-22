boomboombox
===========

This is some sequencer code for an Adafruit Untz (4 x trellis Board) with an Arduino Uno and hardware midi out. It plays eight notes as a stepsequencer and gives them out on an Arduino Uno over MIDI Serial. This is differnt to the actual setup, where a Arduino Leonardo was used to pass the midi via USB - which is bad if you just want to trigger some Hardware-MIDI audio gear.

Resources:
* https://learn.adafruit.com/untztrument-trellis-midi-instrument/
* Uses Midi Libraray 4.2 https://github.com/FortySevenEffects/arduino_midi_library
