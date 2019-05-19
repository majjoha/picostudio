# Picostudio
Picostudio is a four-track live looper inspired by the Teenage Engineering OP-1
and Tascam's Portastudio series.

Each track runs independently which means that the tracks are (intentionally)
not synced. Once recording stops, a track is played immediately. Every track is
recorded onto the devices as a WAV file so it can be exported afterward.

![Picostudio](https://d3r69eeiwn2k86.cloudfront.net/items/0V251N3Z0V3h3q1P2C22/picostudio.png?v=da271bf2)

## Requirements
- Critter and Guitari Organelle

## Controls
- Aux: start recording to the selected track.
- T1: select track 1.
- T2: select track 2.
- T3: select track 3.
- T4: select track 4.
- Knob 1: set start position for the selected track.
- Knob 2: set end position for the selected track.
- Knob 3: set speed for the selected track.
- Knob 4: set volume for the selected track.
- B: enable bounce mode which bounces track 1, track 2, and track 3 to track 4
  once recording starts.
- T: enable tape mode which adds a bit of wobble to the output.

## LED
- Red means recording.
- Teal means bounce mode is enabled.
- Purple means tape mode is enabled.

The colors of the LED are listed in the order of importance, e.g., if both
bounce mode and tape mode are enabled, the LED will be teal. If you then record,
it changes red and returns to teal once the recording stops. If none of the
three modes are enabled, the LED will be unlit.

## License
See [LICENSE](./LICENSE).
