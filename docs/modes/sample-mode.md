# Sample Mode

Sample Mode allows you to record and edit samples directly on the PGB-1.

## Entering Sample Mode

Hold ++cpy-fx++ and press ++edit++ to enter Sample Mode.

## Sample Mode Options

When entering Sample Mode, you can choose:

- **New Sample**: Record a new sample
- **Edit Sample**: Modify an existing sample's start/end points and name

## Recording a New Sample

### Step 1: Select Input Source

Choose which input to record from:

| Input | Description |
|-------|-------------|
| Line In | External audio via 3.5mm jack |
| Internal Mic | Built-in microphone |
| Headset Mic | Microphone on connected headset |

Use ++up++ / ++down++ to adjust input gain.

### Step 2: Start Recording

Press ++a++ to begin recording. The PGB-1 uses a **2-second rolling buffer**:

- Recording continuously captures audio
- When buffer is full, new audio overwrites the oldest
- This lets you capture a sound even slightly after it happens

### Step 3: Stop Recording

Press ++a++ again to stop recording. The captured audio is displayed as a waveform.

### Step 4: Edit Start/End Points

- Use ++left++ / ++right++ to move the start point
- Use ++up++ / ++down++ to move the end point

### Step 5: Preview

The keyboard lights up showing available preview keys:

| Button | Action |
|--------|--------|
| ++1++ | Preview one octave down |
| ++4++ | Preview at original pitch |
| ++8++ | Preview one octave up |
| Other keys | Preview at different pitches |

### Step 6: Set Name

Navigate to the name field and edit the sample name if desired.

### Step 7: Save

1. Press ++a++ to continue
2. Select a sample slot (1-64)
3. Press ++a++ to confirm
4. Navigate to **Yes** and confirm

!!! warning "Overwrite Warning"
    Saving to a slot will overwrite any existing sample in that slot.

## Editing Existing Samples

1. Enter Sample Mode
2. Select **Edit Sample**
3. Choose the sample to edit
4. Adjust start point, end point, and name
5. Save when finished

## Sample Tips

### Recording Quality

- For line input, keep PGB-1 gain low and increase volume on the source device
- This provides better headroom and less noise
- Use the waveform display to check levels

### Multiple Sounds in One Sample

You can record multiple sounds in a single sample and use different start points per step:

1. Record a sample containing two or more sounds
2. In Step Mode, use parameter locks to set different start points
3. Each step can play a different portion of the sample

This technique helps maximize the limited sample slots.

### Sample Slots

The PGB-1 has 64 sample slots. Samples are stored in project memory and persist when the device is turned off.

## Converting Audio Files

You can import audio files from your computer using the online converter tool. See [Importing Samples](../sampling/importing.md) for details.
