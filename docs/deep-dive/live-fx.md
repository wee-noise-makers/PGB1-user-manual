# Live FX

The PGB-1 features 16 live effects that can be activated during playback for
dynamic performances.

## Accessing Live FX

Hold ++cpy-fx++ and press ++1++ to ++16++ to toggle effects.

## Effect Categories

Effects are split into two categories:

- **Sequencing Effects** (left side: 1-4, 9-12) - Affect pattern playback
- **Mixing Effects** (right side: 5-8, 13-16) - Affect audio output

## Sequencing Effects

### Roll Effects

Create note repeats at different speeds:

| Button | Effect | Description |
|--------|--------|-------------|
| ++1++ | Roll 16th | Fast rolls (16th notes) |
| ++2++ | Roll 8th | Medium rolls (8th notes) |
| ++3++ | Roll Quarter | Slow rolls (quarter notes) |
| ++4++ | Roll Beat | Slowest rolls (whole beat) |

Press the button to start the effect, press again to stop. When a roll effect
is enable, you can press another roll effect button to directly switch to
another speed.

### Fill Effects

Add or modify steps automatically:

| Button | Effect | Description |
|--------|--------|-------------|
| ++9++  | Fill Steps | Triggers steps with ["Fill" condition](../modes/step-mode.md) on any tracks |
| ++10++ | Auto-fill Low | Random fills on drum tracks, lower probability |
| ++11++ | Auto-fill High | Random fills on drum tracks, higher probability |
| ++12++ | Auto-fill Build-up | Increasing random fill intensity  on drum tracks |

The auto-fill effects work with drum tracks (Kikc, Snare, Hihat) while the Fill
Steps can be used on any track.

## Mixing Effects

### Filter Effects

Apply filters to the master output:

| Button | Effect | Description |
|--------|--------|-------------|
| ++5++ | Low Pass Filter | Removes high frequencies |
| ++6++ | Band Pass Filter | Removes highs and lows |
| ++7++ | High Pass Filter | Removes low frequencies |

### Filter Sweeps

Animated filter effects:

| Button | Effect | Description |
|--------|--------|-------------|
| ++13++ | LP Sweep | Low pass filter that sweeps |
| ++14++ | BP Sweep | Band pass filter that sweeps |
| ++15++ | HP Sweep | High pass filter that sweeps |

### Stutter Effects

| Button | Effect | Description |
|--------|--------|-------------|
| ++8++ | Stutter 1 | Short audio repeat effect |
| ++16++ | Stutter 2 | Variation of stutter |

## One Effect Per Category

Only one effect of the same type can be active at a time:

- Enabling a filter cancels other filters
- Enabling a roll cancels other rolls
- Enabling a fill cancels other fills

## Combining Effect Categories

You can combine effects from different categories:

- Roll + Filter
- Fill + Stutter
- Filter Sweep + Roll
- Etc.

## Chord Progression Indicator

While holding ++cpy-fx++, the [chord progression](../modes/song-mode.md)
indicator appears on screen. Use this to time your effects to land on specific
chord changes.

## Quick Parameter Control

While holding ++cpy-fx++, the touch strip controls a single parameter for a
selected track. This lets you perform parameter changes during Live FX.

With this feature you can control one of:

 - Synth parameter 1
 - Synth parameter 2
 - Synth parameter 3
 - Synth parameter 4
 - LFO Rate
 - LFO Amplitude
 - Volume
 - Stereo Pan
 - Shuffle

To change the selected track, use the ++left++ or ++right++ buttons while
holding ++cpy-fx++.

To change the selected parameter, use the ++up++ or ++down++ buttons while
holding ++cpy-fx++.

## Performance Tips

### Plan Your FX

- Map out when to use effects in your arrangement
- Practice transitions between song parts
- Know which effects complement each other

### Less Is More

- Subtle filter movements can be very effective
- Don't overuse rolls - save them for impact moments
- Brief stutters are often more effective than sustained ones

### Build and Release

- Use filters and fills to build tension
- Release effects on strong beats
- Combine with song part changes for maximum impact

## See Also

- [Sound Path](../audio-midi/sound-path.md) - Where Live FX fit in the audio chain
- [Trigger Conditions](../modes/step-mode.md) - Setting up Fill conditions
- [Chord Progressions](../modes/song-mode.md) - Using the chord indicator
- [Shortcuts](shortcuts.md) - Quick reference for all controls
