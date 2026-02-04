# MIDI

The PGB-1 can control external MIDI devices, allowing you to integrate it into larger setups.

## MIDI Overview

- Tracks 12-16 are configured as MIDI tracks by default
- Any track can be switched to MIDI mode
- MIDI is sent over USB
- No traditional MIDI DIN connectors

## Enabling MIDI Mode

To switch a track to MIDI mode:

1. Enter Track Mode (++track++)
2. Select the track to configure
3. Navigate to the last settings page (Track Mode)
4. Use ++up++ / ++down++ to select MIDI

## MIDI Output

When a track is in MIDI mode:

- Steps trigger MIDI notes instead of internal sounds
- Note values follow chord progressions (like internal tracks)
- Velocity and other step parameters are transmitted
- Pattern and song structure apply to MIDI output

## USB MIDI Connection

1. Connect PGB-1 to your computer or MIDI host
2. The device appears as a USB MIDI device
3. Route MIDI to your desired destination

### Computer DAW

1. Connect via USB
2. Open your DAW (Ableton, Logic, FL Studio, etc.)
3. Select PGB-1 as MIDI input
4. Route to software instruments

### Hardware Synthesizers

Use a USB MIDI host or computer to route:

1. PGB-1 USB → Computer/Host
2. Computer/Host → Hardware synth MIDI input

## MIDI Tracks

### Default MIDI Tracks

Tracks 12-16 are pre-configured for MIDI:

| Track | Suggested Use |
|-------|---------------|
| 12 | External bass synth |
| 13 | External lead |
| 14 | External pad/chords |
| 15 | External drums |
| 16 | External FX/additional |

### Converting Synth Tracks

Any synth track can be converted to MIDI:

1. This frees up internal synth resources
2. Allows control of more external devices
3. Patterns and steps still work the same

## Chord Transmission

When a MIDI track plays:

- Note in Chord modes send the appropriate chord notes
- Arpeggiator mode sends arpeggio notes
- Chord mode (on supported tracks) sends full chords
- Fixed notes send the specified MIDI note

This means your external synths follow your chord progressions automatically.

## Step Parameters via MIDI

| Step Parameter | MIDI Equivalent |
|----------------|-----------------|
| Note | MIDI Note Number |
| Velocity | MIDI Velocity |
| Duration | Note On/Off timing |
| Condition | Affects whether note is sent |

## Tips

### Latency

USB MIDI can have slight latency. For tight timing:

- Use hardware USB MIDI hosts when possible
- Minimize computer audio buffer sizes
- Test your specific setup

### Multiple Destinations

Use MIDI routing software to send different tracks to different destinations:

- Track 12 → Bass synth
- Track 13 → Lead synth
- Track 14 → Drum machine

### Hybrid Setup

Combine internal and external sounds:

- Internal: Drums, samples
- External: Bass, pads, leads
- Best of both worlds

### Recording

Send MIDI to a DAW to:

- Record performances for editing
- Layer with other tracks
- Apply computer-based processing
