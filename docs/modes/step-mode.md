# Step Mode

Step mode allows you to configure each of the 16 steps for the selected pattern
of the selected track, giving you detailed control over each note's parameters.
In Step mode, pressing one of the ++1++ to ++16++ buttons will select the
corresponding step and trigger it at the same time. The numbers of the selected
pattern and step is shown at the top right of the screen.

![Current pattern and step on screen](../assets/images/current-pattern-and-step-screenshot.png)

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

Determines when the step plays. See [Trigger Conditions](../step-settings/conditions.md) for details:

| Condition | Description |
|-----------|-------------|
| Never | Step never plays |
| Percent (25%, 50%, 75%) | Random chance to play |
| Always | Step always plays |
| Fill | Plays when Fill FX is active |
| Not Fill | Plays when Fill FX is not active |
| X:Y (1:2, 2:2, 1:3, 2:3, etc.) | Plays on the Xth occurrence within every Y pattern loops |

### Page 2: Note Stetings

#### Note

Set what note the step plays. See [Notes & Chords](../step-settings/notes.md) for details:

| Option | Description |
|--------|-------------|
| Fixed Note | Play a specific MIDI note |
| Note in Chord (1-4) | Play specific chord note |
| Arpeggiator | Use the track's arpeggiator setting |
| Chord | Play the full chord |

Use ++a++ to cycle through note modes.

!!! info "Octave Offset"
    In note modes "Note in Chord", "Arpeggiator", and "Chord", the notes can be
    shifted up or down by one or multiple octaves. This is shown as, for
    example, `+1oct` or `-2oct`.

!!! info "Playing full chords"
    From the internal synth engines, only the Chord track can play multiple
    notes simultaneously (polyphony). Therefore it's the only internal track
    where the "Chord" note mode makes sense. However, you can use "Chord" note
    mode with external polyphonic MIDI instruments.

#### Duration

Set how long the note plays.

#### Velocity

Set the note's intensity/volume. Use the touch strip for precise control.

### Page 3: Repeat

Create note repeats (retrigs) within the step:

| Parameter | Description |
|-----------|-------------|
| Count | Number of repeats |
| Rate | Speed of repeats |

### Page 4: Parameter Locks

Set per-step values for synth parameters. This allows each step to have
different sound settings. See [Parameter
Locks](../step-settings/parameter-locks.md) for details.

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

This is powerful for sample tracks where you can select different samples per
step.

## Tips

- Use velocity variations to create groove and dynamics Use parameter locks to
- play different samples on each step of a [sample track](../sampling/sample-tracks.md)

## See Also

- [Step Settings Overview](../step-settings/index.md) - Detailed step configuration
- [Trigger Conditions](../step-settings/conditions.md) - Probability and conditional triggers
- [Notes & Chords](../step-settings/notes.md) - Note selection and chord integration
- [Parameter Locks](../step-settings/parameter-locks.md) - Per-step sound variations
