# Sample Tracks

The PGB-1 has two dedicated sample tracks (Tracks 7 and 8) that play audio samples instead of synthesized sounds.

## Understanding Sample Tracks

### Hardware Limitations

Due to hardware constraints, only two tracks can play samples simultaneously. However, with creative use of features, you can maximize their potential.

### Default Setup

| Track | Default Sample |
|-------|----------------|
| 7 | Cowbell |
| 8 | (varies) |

## Selecting Samples

### Track Default Sample

1. Enter Track Mode (++track++)
2. Select track 7 or 8
3. Navigate to the sample selection page
4. Use ++up++ / ++down++ to choose a sample (1-64)

This sets the default sample for the track.

### Per-Step Sample Selection

Using [parameter locks](../step-settings/parameter-locks.md), each step can play a different sample:

1. Enter Step Mode (++step++)
2. Select a step
3. Navigate past standard settings to the sample parameter
4. Choose a sample for this step

## Playing Multiple Samples on One Track

### Method 1: Parameter Locks

Create a full drum pattern on one track:

| Step | Sample | Result |
|------|--------|--------|
| 1, 5, 9, 13 | Kick | Four-on-floor kick |
| 3, 7, 11, 15 | Hi-hat | Off-beat hats |
| 5, 13 | Snare | Backbeat snare |

All on a single track!

### Method 2: Multiple Sounds in One Sample

Record several sounds in one sample slot:

1. Record "kick - pause - snare - pause - hihat"
2. Use start point parameter locks to select sounds
3. Adjust release for proper length

### Method 3: Combine Both Tracks

- Track 7: Kick and snare pattern
- Track 8: Hi-hats and percussion

## Sample Track Settings

Sample tracks share settings with synth tracks:

| Setting | Use |
|---------|-----|
| Volume | Overall sample level |
| Pan | Stereo position |
| Effect | Drive, reverb, etc. |
| Octave | Pitch shift in octaves |
| Shuffle | Timing swing |

## Step Settings for Samples

### Start Point

Where in the sample playback begins. Use to:

- Skip silence at the beginning
- Access different sounds within a multi-sound sample
- Create variations of the same sample

### Duration/Release

How long the sample plays:

- Short: Tight, punchy sounds
- Long: Full sample with natural decay

### Velocity

Affects sample volume/intensity for that step.

### Repeat

Retrigger the sample multiple times per step for fills and rolls.

## Sample Playback Modes

Samples can be played at different pitches using the chromatic keyboard:

1. Hold ++edit++ to access chromatic keyboard
2. Play notes to trigger the sample at different pitches

In Step Mode, the Note setting can pitch samples:

- Lower notes = lower pitch
- Higher notes = higher pitch

## Tips for Efficient Sample Use

### Maximize Two Tracks

1. Use parameter locks for sample variation
2. Pack multiple sounds per sample slot
3. Use both tracks strategically

### Organize Your Samples

- Keep related samples in adjacent slots
- Use consistent naming
- Reserve specific slots for specific sounds

### Memory Management

The 64 sample slots are shared across the project. Plan your sample allocation:

- Which samples are essential?
- Which can share slots (multiple sounds)?
- What can be synthesized instead?

### Creative Uses

- **Layering**: Both sample tracks play simultaneously
- **Fills**: Use repeat settings for drum fills
- **Melodic samples**: Pitch samples with note settings
- **Textures**: Long ambient samples under synth tracks

## Common Configurations

### Full Drum Kit on One Track

| Steps | Sample | Notes |
|-------|--------|-------|
| 1, 5, 9, 13 | Kick | Main beat |
| 5, 13 | Snare | Backbeat |
| 3, 7, 11, 15 | Closed HH | Off-beats |
| 8 | Open HH | Accent |

### Percussion and Melodic

- **Track 7**: Percussion loops or hits
- **Track 8**: Melodic samples, vocals, or stabs

## See Also

- [Recording Samples](recording.md) - How to record your own samples
- [Importing Samples](importing.md) - Load samples from your computer
- [Parameter Locks](../step-settings/parameter-locks.md) - Per-step sample selection
- [Sound Path](../audio-midi/sound-path.md) - How sample audio is processed
