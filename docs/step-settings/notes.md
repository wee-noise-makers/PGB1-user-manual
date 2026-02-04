# Notes & Chords

The Note setting determines what pitch each step plays and how it interacts with chord progressions.

## Accessing Note Settings

1. Enter Step Mode (press ++step++)
2. Select a step
3. Navigate to page 2 (Note)
4. Press ++a++ to cycle through note modes

## Note Modes

### Chord

**Chords track only** - Plays the full current chord (polyphonic).

This is the only mode that plays multiple notes simultaneously.

### Note in Chord

Plays a specific note from the current chord:

| Setting | Description |
|---------|-------------|
| 1 +0 | Root note, same octave |
| 2 +0 | Second note, same octave |
| 3 +0 | Third note, same octave |
| 4 +0 | Fourth note, same octave |

The second number indicates octave offset:

| Setting | Description |
|---------|-------------|
| 1 +1 | Root note, one octave up |
| 1 -1 | Root note, one octave down |
| 2 +1 | Second note, one octave up |

### Arpeggiator

Uses the track's arpeggiator setting to select which chord note to play. The arpeggiator advances through notes based on its mode (Up, Down, Random, etc.).

### Fixed Note

Plays a specific MIDI note regardless of the current chord. Useful for:

- Notes outside the chord harmony
- Specific sound design needs
- Drum tracks where pitch should be consistent

## Default Track Behavior

Different tracks have different default note behaviors:

| Track | Default Mode |
|-------|--------------|
| Kick, Snare, Hi-Hat | Fixed |
| Bass | Note 1 (Root) |
| Lead | Arpeggiator |
| Chords | Chord |
| Sample | Fixed |

## Working with Chord Progressions

When a chord progression is active:

1. **Chord mode** plays the full chord
2. **Note in Chord** modes follow the progression automatically
3. **Arpeggiator** mode cycles through chord notes
4. **Fixed** mode ignores the chord and plays the set note

This means your bass lines and melodies automatically follow chord changes when using Chord or Note modes.

## Creating Melodies

### Method 1: All Arpeggiator

1. Enable steps in your pattern
2. Set all steps to Arpeggiator
3. Choose an arpeggiator mode in Track Settings
4. Melody automatically generated from chords

### Method 2: Fixed Landing Notes

1. Set important beats (1, 5, 9, 13) to specific chord notes
2. Set other steps to Arpeggiator
3. Creates controlled melody with variation

### Method 3: Fully Composed

1. Set all steps to Note in Chord
2. Choose specific chord notes for each step
3. Full control over melody

### Method 4: Mixed with Fixed Notes

1. Use chord notes for harmonically important steps
2. Use Fixed notes for passing tones or chromatic notes
3. Creates complex melodies that still follow progressions

## Octave Setting

The Octave setting (page 3) shifts the step's note up or down by octaves.

- Use to add bass drops
- Create octave jumps for interest
- Layer the same pattern at different octaves

## Tips

- Bass tracks sound best when emphasizing the root note (Note 1)
- Lead tracks benefit from mixing arpeggiator and specific chord notes
- Use Fixed notes sparingly for color outside the chord
- Octave shifts can add drama to specific steps
