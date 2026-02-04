# Synth Engine Reference

Complete list of synth engines available on the PGB-1.

## Kick Engines (Track 1)

| Engine | Parameters | Description |
|--------|------------|-------------|
| Sine Kick | Punch, Punch Decay, Decay | Classic sine wave kick |
| Sine Click Kick | Punch, Punch Decay, Decay, Click | Sine kick with noise transient |
| Custom Waveform Kick | Punch, Punch Decay, Decay | Custom waveform based kick |
| Custom Click Kick | Punch, Punch Decay, Decay, Click | Custom waveform with click |

## Snare Engines (Track 2)

| Engine | Parameters | Description |
|--------|------------|-------------|
| Snare | Tune, Noise, Decay | Analog-style snare |
| Clap Band Pass | Sync, Noise Decay, Cutoff, Drive | Clap with band pass filter |
| Clap High Pass | Sync, Noise Decay, Cutoff, Drive | Clap with high pass filter |

### Clap Parameter Notes

- **Sync**: Time between noise bursts (higher = longer gaps)
- **Noise Decay**: Length of the noise tail
- **Cutoff**: Filter frequency
- **Drive**: Distortion amount

## Hi-Hat Engines (Track 3)

| Engine | Parameters | Description |
|--------|------------|-------------|
| Hi-Hat | Tune, Decay | Metallic percussion |

**Tip:** Use step Release parameter for open hi-hat effects.

## Bass/Lead Engines (Tracks 4, 5)

These tracks share the same engine library.

### Classic Oscillator Engines

| Engine | P1 | P2 | P3 | P4 |
|--------|----|----|----|----|
| Source Swarm | Detune | Decay | - | - |

### Phase Distortion Engines

| Engine | P1 | P2 | P3 | P4 |
|--------|----|----|----|----|
| PDR Square/Full Sine | Shape | Dist Release | - | - |

### Phaser Engines

| Engine | P1 | P2 | P3 | P4 |
|--------|----|----|----|----|
| Triangle Phaser | Shape | Phase | - | - |
| Sine Phaser | Shape | Phase | - | - |

### Pluck Engines

| Engine | P1 | P2 | P3 | P4 |
|--------|----|----|----|----|
| Sine Pluck | Shape | Cutoff | Resonance | - |
| Triangle Pluck | Shape | Cutoff | Resonance | - |
| Chip Pluck | Shape | Cutoff | Resonance | - |

### Custom Waveform Engines

| Engine | P1 | P2 | P3 | P4 |
|--------|----|----|----|----|
| Custom Waveform Glide | Glide | - | - | - |
| Custom Waveform Phaser | Shape | Phase | - | - |
| Custom Waveform Pluck | Shape | Cutoff | Resonance | - |
| Custom Waveform Echo | Echo | Feedback | - | - |
| Custom Waveform PDR | Shape | Dist Release | - | - |

## Chord Engines (Track 6)

| Engine | Parameters | Description |
|--------|------------|-------------|
| Basic Chords | Shape, Decay | 4-voice polyphonic |
| Mixed Waveforms | Shape, Decay | 4 voices, different waveforms |
| Custom Waveform | Shape, Decay | Custom waveform, 4 voices |

## Sample Tracks (Tracks 7-8)

Sample tracks don't have traditional "engines" but allow sample selection:

| Parameter | Description |
|-----------|-------------|
| Sample | Which sample slot to use (1-64) |
| Start | Playback start point |
| Other | Various playback parameters |

## Audio FX Tracks (Tracks 9-11)

Process audio inputs with effects.

## MIDI Tracks (Tracks 12-16)

Control external MIDI devices. No internal sound engine.

## Engine Categories Summary

| Category | Use |
|----------|-----|
| Sine | Smooth, subby sounds |
| Triangle | Mellow, flute-like |
| Square/Chip | Digital, hollow, retro |
| Phaser | Movement, width |
| Pluck | Percussive, guitar-like |
| PDR | Resonant filter character |
| Custom | User-defined waveform |

## Tips

- Start with simpler engines and explore
- Use LFO to animate engine parameters
- Combine engines across tracks for rich sounds
- Custom waveform engines offer unique possibilities
