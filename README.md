# SysEx File Format

Each SysEx file contains a series of messages phrased like this:

```
F0 00 01 74 ....... F7
```

They are stored sequentially in a single file and can be separated by searching for the start `F0` and end `F7` bytes

## Message structure

Each MIDI block follows the format:

Start byte `F0`

Manufacturer ID `00 01 74` 

Message type 

End Byte `F7`

## Repository Structure

### message_types
Individual pages detailing specific message types will be placed in individual markdown files under the `message_types/` path

### testing_presets
Presets that have been specially configured for isolating the impact of individual changes will be stored under the `testing_presets/` path and there is also a markdown file there explaining each preset and what is special about it


# Random Notes
https://midi.org/midi-1-0-universal-system-exclusive-messages
http://www.gmarts.org/html/axefx_ultra_sysex_1005.html
https://forum.fractalaudio.com/threads/sysex-0x02-midi_get_parameter.123480/
https://wiki.fractalaudio.com/wiki/index.php?title=MIDI_SysEx
