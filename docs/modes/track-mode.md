# Track Mode

Track Mode is where you configure the sounds and settings for each of the 16 tracks on the PGB-1.

## Entering Track Mode

Press ++track++ to enter Track Mode. The Track LED will light up.

## Default Track Assignment

| Track | Default Instrument |
|-------|-------------------|
| 1 | Kick |
| 2 | Snare |
| 3 | Hi-Hat |
| 4 | Bass |
| 5 | Lead |
| 6 | Chords |
| 7-8 | Sample |
| 9-11 | Audio FX |
| 12-16 | MIDI |

!!! info "Track Flexibility"
    All tracks can be configured for MIDI mode to control external devices.

## Selecting Tracks

In Track Mode:

- Press ++1++ to ++16++ to select a track and trigger a preview note
- The selected track name appears at the top left of the screen

To select a track **without** playing a preview:

- Hold ++track++ and press ++1++ to ++16++

## Track Settings Pages

Navigate between pages using ++left++ and ++right++. Each track has multiple settings pages:

### Page 1: Synth Engine

Select the sound engine for the track. Use ++up++ and ++down++ to scroll through available engines. See [Synth Engines](../track-settings/synth-engines.md) for a complete list.

### Page 2: Engine Parameters

Four parameters specific to the selected synth engine. Parameters vary by engine (e.g., Shape, Decay, Cutoff, Resonance).

### Page 3: LFO

Configure the [Low Frequency Oscillator](../track-settings/lfo.md):

| Parameter | Description |
|-----------|-------------|
| Rate | Speed of the LFO |
| Amplitude | Intensity of modulation |
| Shape | Waveform shape + Sync (S) and Loop (L) options |
| Target | Which parameter the LFO modulates |

### Page 4: Volume

Set the track volume level.

### Page 5: Pan

Set the stereo position of the track.

### Page 6: Effect

Select a global mixing effect for the track:

- None (bypass)
- Drive
- Reverb
- Filter
- Beat Crusher

### Page 7: Octave

Shift the track up or down by octaves.

### Page 8: Shuffle

Add swing to the track timing. Higher values delay even-numbered steps.

### Page 9: Arpeggiator Mode

Set how the [arpeggiator](../track-settings/arpeggiator.md) plays chord notes:

- Up
- Down
- Up/Down
- Random
- Order

### Page 10: Arpeggiator Notes

Configure which notes the [arpeggiator](../track-settings/arpeggiator.md) uses.

### Page 11: Track Mode

Switch between internal synth mode and external MIDI controller mode.

## Tips

- Use the touch strip for precise parameter adjustment
- Hold ++cpy-fx++ to access a quick parameter control during playback
- Preview sounds while adjusting parameters by pressing track buttons

## See Also

- [Track Settings Overview](../track-settings/index.md) - Detailed track configuration
- [Synth Engines](../track-settings/synth-engines.md) - Complete engine list
- [Mixing](../track-settings/mixing.md) - Volume, panning, and effects
- [Sound Path](../getting-started/sound-path.md) - How audio flows through the PGB-1
