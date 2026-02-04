# Synth Engines

The PGB-1 features dozens of synthesizer engines across different track types. Each engine has unique parameters that shape its sound.

## Selecting an Engine

1. Enter Track Mode (press ++track++)
2. Select a track
3. Navigate to the first page (Synth Engine)
4. Use ++up++ / ++down++ to scroll through engines

A number indicator shows your position in the engine list.

## Engine Categories

### Kick Engines

Designed for the Kick track (Track 1):

| Engine | Description |
|--------|-------------|
| Sine Kick | Classic sine wave kick |
| Sine Click Kick | Sine kick with noise transient |
| Custom Waveform Kick | Uses the custom waveform |
| Custom Click Kick | Custom waveform with click |

**Common Parameters:**

- Punch - Initial impact intensity
- Punch Decay - How quickly the punch fades
- Decay - Overall sound length

### Snare Engines

Designed for the Snare track (Track 2):

| Engine | Description |
|--------|-------------|
| Snare | Classic analog snare |
| Clap Band Pass | Clap with band pass filter |
| Clap High Pass | Clap with high pass filter |

**Clap Parameters:**

- Sync - Time between noise bursts
- Noise Decay - Tail length
- Cutoff - Filter frequency
- Drive - Distortion amount

### Hi-Hat Engines

Designed for the Hi-Hat track (Track 3):

| Engine | Description |
|--------|-------------|
| Hi-Hat | Metallic percussion |

**Tip:** Use step Release parameter for open hi-hat sounds.

### Bass/Lead Engines

Available on Bass (Track 4) and Lead (Track 5):

| Engine | Description |
|--------|-------------|
| Source Swarm | Detuned oscillator swarm |
| PDR Square/Full Sine | Phase distortion resonance |
| Triangle Phaser | Two triangle waves with phase offset |
| Sine Phaser | Two sine waves with phase offset |
| Sine Pluck | Filtered sine with envelope |
| Triangle Pluck | Filtered triangle with envelope |
| Chip Pluck | Square wave pluck |
| Custom Waveform Glide | Custom wave with portamento |
| Custom Waveform Phaser | Custom wave with phasing |
| Custom Waveform Pluck | Custom wave with filter envelope |
| Custom Waveform Echo | Custom wave with echo |
| Custom Waveform PDR | Custom wave phase distortion |

**Phase Distortion Resonance (PDR) Parameters:**

- Shape/Distortion - Waveform distortion amount
- Distort Release - How quickly distortion decays
- Additional engine-specific parameters

**Phaser Parameters:**

- Shape - Waveform shaping
- Phase - Offset between oscillators

**Pluck Parameters:**

- Shape - Waveform shape
- Cutoff - Filter starting frequency
- Resonance - Filter emphasis
- Release - Decay time

### Chord Engines

For the Chords track (Track 6):

| Engine | Description |
|--------|-------------|
| Basic Chords | Four-voice polyphonic |
| Mixed Waveforms | Four voices with different waves |
| Custom Waveform | Uses custom waveform for all voices |

Chord engines are the only polyphonic engines - they can play multiple notes simultaneously.

### Sample Engines

For Sample tracks (Tracks 7-8):

Sample tracks play audio samples rather than synthesized sounds. The engine parameter selects which sample slot to use by default.

### Audio FX Engines

For FX tracks (Tracks 9-11):

These tracks process audio from the audio inputs through various effects.

## Custom Waveform Engines

Engines with "Custom Waveform" in the name use the waveform you draw in the Custom Waveform menu. See [Custom Waveforms](../custom-waveforms.md) for details.

## Engine Parameters

Each engine has up to 4 parameters accessible on the second settings page:

- **P1** - First parameter (often shape or main character)
- **P2** - Second parameter (often secondary control)
- **P3** - Third parameter (often filter or modulation)
- **P4** - Fourth parameter (often decay or release)

Use ++up++ / ++down++ to adjust values. Use the touch strip for precise control.

## Tips

- Try different engines to find sounds that fit your track
- Use LFO to automate engine parameters
- Parameter locks can change engine parameters per step
