# Importing Samples

You can convert audio files from your computer into PGB-1 compatible samples using the online converter tool.

## Using the Online Converter

### Step 1: Access the Tool

Visit the Wee Noise Makers website:
[weenoisemakers.com/pgb-1](https://weenoisemakers.com/pgb-1)

Scroll to the bottom of the page to find the sample converter widget.

### Step 2: Select Your Audio File

1. Click **Choose File**
2. Select an audio file from your computer
3. Supported formats include WAV, MP3, and other common formats

### Step 3: Preview and Adjust

- The waveform displays on screen
- Click the play button to preview
- Adjust the name field if desired

### Step 4: Select Sample Slot

Choose which slot (1-64) to save the sample to.

!!! warning "Slot Overwrite"
    The selected slot will be overwritten when you transfer to the PGB-1.

### Step 5: Export

Click **Export** to download the converted file.

The file will be a `.uf2` file named something like `pgb1-sample.uf2`.

## Transferring to PGB-1

### Step 1: Enter Update Mode

1. Connect PGB-1 to your computer with a USB cable
2. Turn on the device
3. Press ++menu++
4. Navigate to **Update Mode**
5. Press ++a++ to enter, then confirm

The PGB-1 displays "UP" on the keyboard LEDs.

### Step 2: Transfer the File

1. The PGB-1 appears as a USB drive called **RPI-RP2**
2. Drag and drop the `.uf2` file into the drive
3. Wait for the PGB-1 to reboot

### Step 3: Verify

1. Go to a sample track (7 or 8)
2. Navigate to the sample selection
3. Your new sample should be in the slot you selected

!!! tip "Good USB Cable"
    Use a high-quality USB cable for reliable transfers.

## Converting Tips

### Audio Preparation

Before converting, consider:

- **Trim** your audio to remove silence
- **Normalize** levels for consistent volume
- **Convert to mono** if your source is stereo (or let the tool do it)
- Keep samples **under 2 seconds**

### Recommended Audio Editors

- **Audacity** (free, cross-platform)
- **Adobe Audition**
- **Logic Pro / GarageBand** (Mac)
- **Ableton Live**

### Batch Processing

For multiple samples:

1. Prepare and export each sample
2. Select different slots for each
3. Transfer all `.uf2` files one at a time

## Organizing Your Sample Library

### Sample Slot Strategy

| Slots | Content |
|-------|---------|
| 1-16 | Drums (kicks, snares, hats) |
| 17-32 | Percussion |
| 33-48 | Melodic (bass, stabs, chords) |
| 49-64 | FX (risers, impacts, vocals) |

### Project-Specific Samples

Each project can use the same sample slots. Consider having:

- A core library that stays constant
- Project-specific samples in designated slots

## Troubleshooting

### Sample Doesn't Appear

- Ensure you selected the correct slot
- Check that the transfer completed (PGB-1 rebooted)
- Try the transfer again with a different cable

### Audio Quality Issues

- Start with high-quality source audio
- Avoid over-compressing before conversion
- Check your original file plays correctly
