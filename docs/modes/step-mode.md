# Step Mode

Step Mode allows you to configure individual steps in a pattern, giving you detailed control over each note's parameters.

## Entering Step Mode

Press ++step++ to enter Step Mode. The Step LED will light up.

## Selecting Steps

In Step Mode:

- Press ++1++ to ++16++ to select a step and trigger it
- The selected pattern and step numbers appear at the top right of the screen

To select a step **without** triggering it:

- Hold ++step++ and press ++1++ to ++16++

## Step Settings Pages

Navigate between pages using ++left++ and ++right++:

### Page 1: Trigger Condition

Determines when the step plays:

| Condition | Description |
|-----------|-------------|
| Never | Step never plays |
| Percent (25%, 50%, 75%) | Random chance to play |
| Always | Step always plays |
| Fill | Only plays when Fill FX is active |
| Not Fill | Only plays when Fill FX is not active |
| 1:2, 1:3, 1:4 | Plays every 2nd, 3rd, or 4th time |

### Page 2: Note

Set what note the step plays:

| Option | Description |
|--------|-------------|
| Chord | Play the full chord (Chords track only) |
| Note in Chord (1-4) | Play specific chord note |
| Arpeggiator | Use the track's arpeggiator setting |
| Fixed Note | Play a specific MIDI note |

Use ++a++ to cycle through note modes.

### Page 3: Octave Offset

Shift the note up or down by octaves from the chord's octave.

### Page 4: Duration

Set how long the note plays.

### Page 5: Velocity

Set the note's intensity/volume. Use the touch strip for precise control.

### Page 6: Repeat

Create note repeats (retrigs) within the step:

| Parameter | Description |
|-----------|-------------|
| Count | Number of repeats |
| Rate | Speed of repeats |

### Page 7+: Parameter Locks

Set per-step values for synth parameters. This allows each step to have different sound settings.

## Working with Steps

### Enabling/Disabling Steps

1. Press ++edit++ to enter edit mode
2. Press ++1++ to ++16++ to toggle steps on/off
3. Press ++edit++ again to exit edit mode

### Using Parameter Locks

Parameter locks let you change synth parameters for individual steps:

1. Select a step in Step Mode
2. Navigate to the parameter lock pages (after velocity/repeat)
3. Adjust the parameter value
4. The step will now play with that specific parameter value

This is powerful for sample tracks where you can select different samples per step.

## Tips

- Use velocity variations to create groove and dynamics
- Combine trigger conditions with copy/paste for complex patterns
- Use parameter locks to play different samples on each step of a sample track
