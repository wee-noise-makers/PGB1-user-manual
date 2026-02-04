# LFO (Low Frequency Oscillator)

Each track has its own LFO that can automatically modulate parameters over time, adding movement and expression to your sounds.

## Accessing LFO Settings

1. Enter Track Mode (press ++track++)
2. Select a track
3. Navigate to page 3 (LFO settings)

## LFO Parameters

### Rate

Controls the speed of the LFO oscillation.

- Lower values = slower modulation
- Higher values = faster modulation

### Amplitude

Controls how much the LFO affects the target parameter.

- 0 = No effect
- Higher values = More dramatic modulation

### Shape

Selects the waveform shape used for modulation:

| Shape | Description |
|-------|-------------|
| Sine | Smooth, natural modulation |
| Triangle | Linear rise and fall |
| Saw Up | Rising ramp |
| Saw Down | Falling ramp |
| Square | Abrupt on/off switching |
| Random | Step changes at random values |

#### Shape Modifiers

The Shape setting also includes two important modifiers indicated by small letters:

**S - Sync**

- When enabled, the LFO resets every time a note is played
- Useful for consistent modulation at note start
- Creates predictable, rhythmic effects

**L - Loop**

- When enabled, the LFO continuously cycles
- When disabled, the LFO runs once per note (like an envelope)

### Target

Selects which parameter the LFO modulates:

| Target | Effect |
|--------|--------|
| P1 | Modulates engine parameter 1 |
| P2 | Modulates engine parameter 2 |
| P3 | Modulates engine parameter 3 |
| P4 | Modulates engine parameter 4 |
| Volume | Modulates track volume (tremolo) |
| Pan | Modulates stereo position (auto-pan) |

## LFO Modes

By combining Sync and Loop settings, you can create different behaviors:

| Sync | Loop | Behavior |
|------|------|----------|
| Off | On | Free-running continuous LFO |
| On | On | LFO resets on each note, then loops |
| Off | Off | Free-running single cycle |
| On | Off | **Envelope mode** - runs once per note |

### Envelope Mode

When Sync is ON and Loop is OFF, the LFO acts like an envelope:

- Triggers on each note
- Runs through one cycle
- Stays at final value until next note

This is useful for:

- Filter sweeps that decay with each note
- Pitch drops on kicks
- Attack transients

## Practical Examples

### Wobble Bass

1. Select Bass track
2. Set LFO Target to P2 (usually filter cutoff)
3. Set Shape to Sine with Loop ON
4. Adjust Rate to match your tempo
5. Set Amplitude to taste

### Subtle Detune

1. Select Lead track with Phaser engine
2. Set LFO Target to P2 (phase offset)
3. Set Shape to Sine, slow Rate
4. Low Amplitude for subtle movement

### Gated Pad

1. Select Chords track
2. Set LFO Target to Volume
3. Set Shape to Square with Sync ON
4. Adjust Rate for rhythmic gating

### Pluck Filter Sweep

1. Select Bass with Pluck engine
2. Set LFO Target to P2 (cutoff)
3. Set Shape to Saw Down
4. Enable Sync, disable Loop
5. Fast decay creates a pluck effect

## Tips

- Start with low Amplitude and increase gradually
- Use Sync for rhythmic effects
- Envelope mode (Sync ON, Loop OFF) is powerful for per-note effects
- The touch strip can quickly adjust LFO parameters during performance
